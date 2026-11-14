<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rpu4vx-uy"/><path class="w18xxwbvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lucky-draw-box" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rpu4vx-uy {
  d: path("M5.625 9.5h12.75A2.625 2.625 0 0 1 21 12.125v6.75a2.625 2.625 0 0 1-2.625 2.625H5.625A2.625 2.625 0 0 1 3 18.875v-6.75A2.625 2.625 0 0 1 5.625 9.5M4.5 7.5l1.05-1.4a1.5 1.5 0 0 1 1.2-.6h10.5a1.5 1.5 0 0 1 1.2.6l1.05 1.4a1.25 1.25 0 0 1-1 2h-13a1.25 1.25 0 0 1-1-2m5 0h5");
}

.w18xxwbvs {
  d: path("M9.75 13.75c0-1.25 1-2 2.25-2s2.25.75 2.25 2S12 15 12 16.5m0 2.5h.01");
}

</style>
