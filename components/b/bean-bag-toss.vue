<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uaiqu6dxr"/><path class="a6qdlxbht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bean-bag-toss" /></template>
<style>
.a6qdlxbht {
  d: path("M10 16.75a3 1.75 0 1 0 6 0a3 1.75 0 1 0-6 0Zm5.055-14.618l5.313 1.423l-1.423 5.313l-5.313-1.423ZM3 9.5q2.5-5 8-5.75");
}

.uaiqu6dxr {
  d: path("M2.5 21.5L7 12h14.5L17 21.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
