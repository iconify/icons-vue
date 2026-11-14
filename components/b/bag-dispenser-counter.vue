<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c5_mpgb_y"/><path class="u5eqt7_wb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bag-dispenser-counter" /></template>
<style>
.c5_mpgb_y {
  d: path("M5.125 13.5h13.75a2.625 2.625 0 0 1 2.625 2.625v2.75a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 18.875v-2.75A2.625 2.625 0 0 1 5.125 13.5m-2.625 0l3-3.5h13l3 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u5eqt7_wb {
  d: path("M8 11.75V2.5h2.5V6h3V2.5H16v9.25m-10 0h12");
}

</style>
