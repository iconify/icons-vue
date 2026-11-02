<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h7139cbvh"/><path class="ty2xixbmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-candlestick-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h7139cbvh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 7v3a3 3 0 1 1-6 0V7a3 3 0 1 1 6 0M8 17v1a3 3 0 1 1-6 0v-1a3 3 0 1 1 6 0m8.236-1.168a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338");
}

.ty2xixbmc {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 17a2 2 0 1 1 4 0v1a2 2 0 1 1-4 0Zm7-10a2 2 0 1 1 4 0v3a2 2 0 1 1-4 0Zm7 10a2 2 0 1 1 4 0a2 2 0 0 1-4 0M5 12v3m0 5v1m7-18v2m0 7v3m7-3v3m0 4v2");
}

</style>
