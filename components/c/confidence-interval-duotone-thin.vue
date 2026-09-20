<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dktry7bqc"/><path class="obkj69_do"/><path class="w7e53rb8m"/><path class="rv-5y_bth"/><path class="t2rd8jbcx"/><path class="z8g2jgblp"/><path class="h_p-57bvu"/><path class="bo51iypxr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:confidence-interval-duotone-thin" /></template>
<style>
.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.dktry7bqc {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.h_p-57bvu {
  d: path("M19 8v8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.obkj69_do {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rv-5y_bth {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t2rd8jbcx {
  d: path("M5 8v8");
}

.w7e53rb8m {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 12h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z8g2jgblp {
  d: path("M5 12h14");
}

</style>
