<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="anvi28hfv"/><path class="h9piesnqy"/><path class="jyx-3ofrk"/><path class="zmj1nccll"/><path class="pcl5pkbcw"/><path class="wzsyjh0wp"/><path class="votyijv0m"/><path class="prbp3oa5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cpu-duotone-regular" /></template>
<style>
.anvi28hfv {
  fill: currentColor;
  d: path("M13.5 5H16a3 3 0 0 1 3 3v8a3 3 0 0 1 -3 3H8a3 3 0 0 1 -3 -3V8l3 -3h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.h9piesnqy {
  fill: currentColor;
  d: path("M8.5 10.5a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jyx-3ofrk {
  d: path("M13.5 5H16a3 3 0 0 1 3 3v8a3 3 0 0 1 -3 3H8a3 3 0 0 1 -3 -3V8l3 -3h2.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pcl5pkbcw {
  d: path("M2 9h3");
}

.prbp3oa5j {
  d: path("M19 15h3");
}

.votyijv0m {
  d: path("M19 9h3");
}

.wzsyjh0wp {
  d: path("M2 15h3");
}

.zmj1nccll {
  d: path("M8.5 10.5a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

</style>
