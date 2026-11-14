<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z14xr7vdq"/><path class="hv93gvb-u"/><path class="q3mnfrbtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:city-hall-search" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hv93gvb-u {
  d: path("M7.25 11a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0m8.25 3.5l4 4");
}

.q3mnfrbtv {
  d: path("M10.75 13.5V9L12 8l1.25 1v4.5");
}

.z14xr7vdq {
  d: path("m3.636 4.216l4.526-1.132a1.5 1.5 0 0 1 .678-.011l6.32 1.354a1.5 1.5 0 0 0 .678-.011l3.798-.95A1.5 1.5 0 0 1 21.5 4.921v11.408a1.5 1.5 0 0 1-1.136 1.455l-4.526 1.132a1.5 1.5 0 0 1-.678.011l-6.32-1.354a1.5 1.5 0 0 0-.678.011l-3.798.95A1.5 1.5 0 0 1 2.5 17.079V5.671a1.5 1.5 0 0 1 1.136-1.455");
}

</style>
