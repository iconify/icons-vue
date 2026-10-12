<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="t54wz0zru"/><circle class="fw2awacyd"/><path class="gjm7u7v1y"/><path class="qyrds1bwu"/><path class="ea5fdbqox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:instant-camera" /></template>
<style>
.ea5fdbqox {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 17.75h10.5");
}

.fw2awacyd {
  cx: 12px;
  cy: 11.25px;
  r: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.gjm7u7v1y {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 6.25h2.5");
}

.qyrds1bwu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.75 6.25h.01");
}

.t54wz0zru {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3.5px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
