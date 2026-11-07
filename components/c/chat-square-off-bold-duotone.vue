<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy1zqfbpa.css';
import '../../css/e/erra6gogy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yy1zqfbpa"/><path class="erra6gogy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-square-off-bold-duotone" /></template>
