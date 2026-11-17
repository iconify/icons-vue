<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qb-3c8bsq"/><path class="g5s6ahb7t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-solar-panel-corner-duocolor-sharp" /></template>
<style>
.g5s6ahb7t {
  d: path("M8 21H4V10l8-7l5.714 5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qb-3c8bsq {
  stroke-opacity: 0.4;
  d: path("M17 21h-4l1-8h3m0 0h3l1 8h-4m-3-4h6m-3-4v8");
}

</style>
