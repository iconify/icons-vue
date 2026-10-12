<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="td5f-we4b"/><rect class="qb1idws_x"/><rect class="atb6z3uyg"/><path class="alah3sbub"/><path class="szim-38ur"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chart-grow" /></template>
<style>
.alah3sbub {
  d: path("m3.75 11.75l5.5-5.5l3 3l6.5-6.5");
}

.atb6z3uyg {
  width: 3.5px;
  height: 10px;
  x: 16.75px;
  y: 10.25px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qb1idws_x {
  width: 3.5px;
  height: 7px;
  x: 10.25px;
  y: 13.25px;
  rx: 1px;
}

.szim-38ur {
  d: path("M14.25 2.75h4.5v4.5");
}

.td5f-we4b {
  width: 3.5px;
  height: 4px;
  x: 3.75px;
  y: 16.25px;
  rx: 1px;
}

</style>
