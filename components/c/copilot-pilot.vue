<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="q0ext1bfu"/><path class="ydo5nz_1d"/><rect class="ll3qaspso"/><path class="ozp811btq"/><path class="iad6w1qmg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:copilot-pilot" /></template>
<style>
.iad6w1qmg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.75 19.5c0-2.6 1.7-4.25 3.75-4.25s3.75 1.65 3.75 4.25a1 1 0 0 1-1 1h-5.5a1 1 0 0 1-1-1");
}

.ll3qaspso {
  width: 6.5px;
  height: 5.5px;
  x: 14.25px;
  y: 6.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.ozp811btq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.25 9.25h.01m2.49 0h.01");
}

.q0ext1bfu {
  cx: 6.5px;
  cy: 8.75px;
  r: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ydo5nz_1d {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 19.5c0-2.6 1.7-4.25 3.75-4.25s3.75 1.65 3.75 4.25a1 1 0 0 1-1 1h-5.5a1 1 0 0 1-1-1M17.5 3.25v2.5");
}

</style>
