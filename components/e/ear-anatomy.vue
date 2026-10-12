<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="z39_sdbig"/><path class="dnq_tv0di"/><path class="zajpd0huc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ear-anatomy" /></template>
<style>
.dnq_tv0di {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 12H15a3 3 0 1 1 3 3");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z39_sdbig {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.34 5.45a8 8 0 1 0-1.85 14.07a1.63 1.63 0 0 0-1.12-3.06a4.75 4.75 0 1 1 1.1-8.35a1.63 1.63 0 0 0 1.87-2.66");
}

.zajpd0huc {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18 12h.01");
}

</style>
