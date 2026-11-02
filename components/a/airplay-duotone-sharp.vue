<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n61l8cx1j"/><path class="xnr4lx0yd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:airplay-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.n61l8cx1j {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 4h18v11H3Z");
}

.xnr4lx0yd {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 15H3V4h18v11h-3m-6 5H7l5-5l5 5z");
}

</style>
