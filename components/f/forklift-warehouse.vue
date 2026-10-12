<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b2wfsibao"/><path class="p0ly8bctm"/><rect class="faoelnbbx"/><circle class="jul19qooo"/><circle class="c_j4n_qjl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:forklift-warehouse" /></template>
<style>
.b2wfsibao {
  d: path("M2.75 14.5v-4q0-1 1-1H5q1 0 1 1v.5q0 1 1 1h3.5q1 0 1 1v1.5q0 1-1 1H3.75q-1 0-1-1");
}

.c_j4n_qjl {
  cx: 10.25px;
  cy: 19.75px;
  r: 1.25px;
}

.faoelnbbx {
  width: 3.75px;
  height: 4.5px;
  x: 17.5px;
  y: 14.75px;
  rx: 0.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jul19qooo {
  cx: 4.75px;
  cy: 19.75px;
  r: 1.25px;
}

.p0ly8bctm {
  d: path("M4.25 9.5V4.75h6.25V12m1 1h3m0-9.5v15.75h6.75");
}

</style>
