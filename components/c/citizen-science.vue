<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrptsabxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:citizen-science" /></template>
<style>
.xrptsabxu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.096 21H5c-.6 0-1-.4-1-1c0-3.3 3.6-5.5 8-5.5q.743 0 1.451.082M8 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm8.25 6.5h4m-3 0v2.75L15 21.5h6.5l-2.25-4.75V14");
}

</style>
