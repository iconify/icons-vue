<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly-_et2sc.css';
import '../../css/x/xp5j9_8ij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ly-_et2sc"/><path class="xp5j9_8ij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:call-chat-bold-duotone" /></template>
