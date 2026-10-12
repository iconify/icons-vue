<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="xrf4e9f4i"/><circle class="hyfgy206y"/><path class="duil7l32j"/><rect class="dz2sj_x2u"/><rect class="gmlridchp"/><path class="fw6ra5b4x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:audio-recorder" /></template>
<style>
.duil7l32j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 9.25L8.4 6.1M14 9.25l1.6-3.15");
}

.dz2sj_x2u {
  width: 13.5px;
  height: 12px;
  x: 5.25px;
  y: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.fw6ra5b4x {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 18.5h.01m2.99 0h.01m2.99 0h.01");
}

.gmlridchp {
  width: 8px;
  height: 4px;
  x: 8px;
  y: 11.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.hyfgy206y {
  cx: 16.5px;
  cy: 4.5px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xrf4e9f4i {
  cx: 7.5px;
  cy: 4.5px;
  r: 1.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
