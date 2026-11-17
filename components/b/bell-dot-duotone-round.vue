<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mgcyljbbk"/><path class="m8wm8-4uy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bell-dot-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m8wm8-4uy {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 13zc0 1 1 1 1 2a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2c0-1 1-1 1-2V9a6 6 0 0 1 6-6M9 17v1a3 3 0 0 0 6 0v-1m0-11a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

.mgcyljbbk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19 13c0 1 1 1 1 2a2 2 0 0 1-2 2h-3v1a3 3 0 1 1-6 0v-1H6a2 2 0 0 1-2-2c0-1 1-1 1-2V9a6 6 0 0 1 6-6a7.62 7.62 0 0 0 .663 7.224C13.322 12.709 16.175 13.402 19 13");
}

</style>
