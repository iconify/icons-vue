<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="az536ibkg"/><path class="pkquy3oor"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cursor-not-allowed-duotone-round" /></template>
<style>
.az536ibkg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15.316 6.051a1 1 0 0 1-.073 1.919l-2.313.578a2.416 2.416 0 0 1-.223 3.159l-1 1a2.416 2.416 0 0 1-3.159.223l-.578 2.313a1 1 0 0 1-1.919.073l-4-12a1.001 1.001 0 0 1 1.265-1.265Z");
}

.ft5dv1b6b {
  fill: none;
}

.pkquy3oor {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3 3l12 4l-4 1l1 1a1.414 1.414 0 0 1 0 2l-1 1a1.414 1.414 0 0 1-2 0l-1-1l-1 4zm16 11a3.606 3.606 0 1 1-4 6a3.606 3.606 0 0 1 4-6m-4 6l4-6");
}

</style>
