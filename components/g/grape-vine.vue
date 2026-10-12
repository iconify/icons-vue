<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ba3897b-m"/><circle class="m3m9nrmce"/><circle class="hlk9z-gue"/><circle class="cxzxrma2a"/><circle class="k0kd3bb_a"/><circle class="sjcg-y_6j"/><circle class="zoxheb0fq"/><path class="q6eglzb7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:grape-vine" /></template>
<style>
.ba3897b-m {
  d: path("M2.75 5.25q3.75-2.25 7.5 0c3.75 2.25 5.5 1.5 8 0c1.25-.75 2.25-1.5 3-2.5M9 5.25V8.5");
}

.cxzxrma2a {
  cx: 13.5px;
  cy: 10px;
  r: 1.5px;
}

.hlk9z-gue {
  cx: 9px;
  cy: 10px;
  r: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k0kd3bb_a {
  cx: 6.75px;
  cy: 13.9px;
  r: 1.5px;
}

.m3m9nrmce {
  cx: 4.5px;
  cy: 10px;
  r: 1.5px;
}

.q6eglzb7l {
  d: path("M16 6q-2.72 7.1 4.5 9.5Q23.22 8.4 16 6");
}

.sjcg-y_6j {
  cx: 11.25px;
  cy: 13.9px;
  r: 1.5px;
}

.zoxheb0fq {
  cx: 9px;
  cy: 17.8px;
  r: 1.5px;
}

</style>
