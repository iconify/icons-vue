<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dktry7bqc"/><path class="sp0kpg66c"/><path class="jk_vepbzc"/><path class="c2v0fbcno"/><path class="t2rd8jbcx"/><path class="z8g2jgblp"/><path class="h_p-57bvu"/><path class="bo51iypxr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:confidence-interval-duotone-regular" /></template>
<style>
.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.c2v0fbcno {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
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

.jk_vepbzc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 12h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sp0kpg66c {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t2rd8jbcx {
  d: path("M5 8v8");
}

.z8g2jgblp {
  d: path("M5 12h14");
}

</style>
