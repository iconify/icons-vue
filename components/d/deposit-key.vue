<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="tab64gb6d"/><path class="rxjktnbse"/><path class="uv_686byc"/><rect class="bjg6r9bta"/><path class="qgpa04dos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:deposit-key" /></template>
<style>
.bjg6r9bta {
  width: 12.5px;
  height: 8.5px;
  x: 8.75px;
  y: 12.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.qgpa04dos {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 15.5h12.5m-12.5 3h12.5");
}

.rxjktnbse {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 7.5h.01");
}

.tab64gb6d {
  cx: 6.5px;
  cy: 7.5px;
  r: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uv_686byc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 7.5h11m-3.75 0V10m3-2.5V10");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
