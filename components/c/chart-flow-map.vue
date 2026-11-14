<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="odlalp_bc"/><path class="ed_m5qbpk"/><path class="c5m06pb_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-flow-map" /></template>
<style>
.c5m06pb_n {
  d: path("M15.25 11.75L18 11.5l-.5-2.75");
}

.ed_m5qbpk {
  d: path("M5.5 16c2-6.5 8-8 12.5-4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.odlalp_bc {
  d: path("M3.526 4.658L8.06 3.147a1.5 1.5 0 0 1 .886-.02l6.108 1.746a1.5 1.5 0 0 0 .886-.02l3.586-1.195A1.5 1.5 0 0 1 21.5 5.081v12.838a1.5 1.5 0 0 1-1.026 1.423l-4.534 1.511a1.5 1.5 0 0 1-.886.02l-6.108-1.746a1.5 1.5 0 0 0-.886.02l-3.586 1.195A1.5 1.5 0 0 1 2.5 18.919V6.081a1.5 1.5 0 0 1 1.026-1.423M8.5 3v4.5m7-2.5v3m-7 9v2m7-.5V21");
}

</style>
