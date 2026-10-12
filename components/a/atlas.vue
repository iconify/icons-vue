<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="x00qgzx7x"/><path class="eqr1q2f2d"/><circle class="u1f8d-qjb"/><path class="vew-d5b-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:atlas" /></template>
<style>
.eqr1q2f2d {
  d: path("M7.75 2.75v18.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u1f8d-qjb {
  cx: 13.5px;
  cy: 12px;
  r: 3.25px;
}

.vew-d5b-c {
  d: path("M10.25 12h6.5M13.5 8.75v6.5");
}

.x00qgzx7x {
  width: 14.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
