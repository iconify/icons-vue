<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wc5z8dbsh"/><path class="dgtsa1nsc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cursor-not-allowed-duotone-sharp" /></template>
<style>
.dgtsa1nsc {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3 3l12 4l-4 1l2 2l-3 3l-2-2l-1 4zm16 11a3.606 3.606 0 1 1-4 6a3.606 3.606 0 0 1 4-6m-4 6l4-6");
}

.ft5dv1b6b {
  fill: none;
}

.wc5z8dbsh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15.316 6.051a1 1 0 0 1-.073 1.919l-2.287.572l.751.751a1 1 0 0 1 0 1.414l-3 3a1 1 0 0 1-1.414 0l-.751-.751l-.572 2.287a1 1 0 0 1-1.919.073l-4-12a1.001 1.001 0 0 1 1.265-1.265Z");
}

</style>
