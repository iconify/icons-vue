<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="x-5rv1bsf"/><path class="y2cyi5bsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:group-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.x-5rv1bsf {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 11h5a3 3 0 0 1 3 3v1a3 3 0 0 1-3 3h-3a3 3 0 0 1-3-3v-3a1 1 0 0 1 1-1");
}

.y2cyi5bsb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 12H9a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2h3a2 2 0 0 1 2 2zm-4 0h5a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2h-3a2 2 0 0 1-2-2zM3 6a3 3 0 0 1 3-3m12 0a3 3 0 0 1 3 3m0 12a3 3 0 0 1-3 3M6 21a3 3 0 0 1-3-3");
}

</style>
