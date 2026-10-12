<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zl065ca8s"/><circle class="k6r3zgz2g"/><circle class="i_laebm5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:car-service" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i_laebm5d {
  cx: 14px;
  cy: 19.25px;
  r: 2px;
}

.k6r3zgz2g {
  cx: 6.75px;
  cy: 19.25px;
  r: 2px;
}

.zl065ca8s {
  d: path("M20.5 8a3.5 3.5 0 1 1 0-3.5M18.75 4l1.75.5l.5-1.75M2.75 16.25V14.5q0-1 .97-1.22l1.31-.31q.97-.22 1.52-1.05l.9-1.34Q8 9.75 9 9.75h2.5q1 0 1.55.83l.9 1.34q.55.83 1.54.97l1.52.22q.99.14.99 1.14v2q0 1-1 1H3.75q-1 0-1-1");
}

</style>
