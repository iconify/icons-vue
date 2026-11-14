<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ubgs56bfy"/><path class="ytnlb68ov"/><path class="wla4mcc_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:corner-kick" /></template>
<style>
.ubgs56bfy {
  d: path("M21.5 3v18.5H3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wla4mcc_w {
  fill: currentColor;
  d: path("m13 11l2 1.5l-.75 2.25h-2.5L11 12.5Z");
}

.ytnlb68ov {
  d: path("M17.5 21.5a4 4 0 0 1 4-4M8 13a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

</style>
