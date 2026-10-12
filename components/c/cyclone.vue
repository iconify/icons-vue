<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="tk2_d1t0v"/><path class="xvzerlwtb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cyclone" /></template>
<style>
.tk2_d1t0v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 12a3.5 3.5 0 0 1 7 0a5.25 5.25 0 0 1-10.5 0a7 7 0 0 1 14 0a8.75 8.75 0 0 1-17.5 0");
}

.xvzerlwtb {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.75 12h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
