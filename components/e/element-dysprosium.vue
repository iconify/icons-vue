<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g6ulkabjn"/><path class="x_hxaobyx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:element-dysprosium" /></template>
<style>
.g6ulkabjn {
  d: path("M2.5 2.5h19v19h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x_hxaobyx {
  d: path("M5.5 11h2a3.5 3.5 0 0 1 0 7h-2Zm8.5 2.5l2.25 4.25m2.25-4.25l-3.25 6M7 5.25Q5.5 5.75 5.5 7a1 1 0 1 0 2 0a1 1 0 1 0-2 0m5-1.75Q9 5.75 9 7a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>
