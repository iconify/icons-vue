<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi9mdulmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:frame-source-sharp" /></template>
<style>
.pi9mdulmg {
  fill: currentColor;
  d: path("M8.6 14.889L5.712 12L8.6 9.111l.689.714L7.114 12l2.175 2.175zm6.8 0l-.688-.714L16.887 12l-2.175-2.175l.688-.713L18.288 12zM4 20v-5h1v4h4v1zm11 0v-1h4v-4h1v5zM4 9V4h5v1H5v4zm15 0V5h-4V4h5v5z");
}

</style>
