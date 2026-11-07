<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xp5j9_8ij.css';
import '../../css/x/x6g9eebag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp5j9_8ij"/><path class="x6g9eebag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:call-chat-rounded-bold-duotone" /></template>
