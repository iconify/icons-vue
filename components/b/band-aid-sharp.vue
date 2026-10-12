<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="yrpl9fyjc"/><path class="p5d_q1bsv"/><path class="qjigr-bze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:band-aid-sharp" /></template>
<style>
.p5d_q1bsv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.88 12L12 9.88l.53-.529l.53.529l1.06 1.06l.529.53l-.529.53L12 14.12l-.53.529l-.53-.529l-1.06-1.06l-.529-.53z");
}

.qjigr-bze {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.24 7.76h.01m-8.49 8.48h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.yrpl9fyjc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.93 13.41l8.48-8.48a4 4 0 0 1 5.66 5.66l-8.48 8.48a4 4 0 0 1-5.66-5.66Z");
}

</style>
