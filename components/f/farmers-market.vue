<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kx1n2m8_y"/><circle class="u-10n5mpy"/><circle class="oof2upb3i"/><circle class="szw-6_b5h"/><rect class="nljwxbb2v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:farmers-market" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kx1n2m8_y {
  d: path("M5.3 2.75h13.4q.8 0 1.03.77l1.29 4.21q.23.77-.57.77H3.55q-.8 0-.57-.77l1.29-4.21q.23-.77 1.03-.77m3.95.5L8.75 8m6-4.75l.5 4.75m-12.5.5v12.75M21.25 8.5v12.75");
}

.nljwxbb2v {
  width: 18.5px;
  height: 3.5px;
  x: 2.75px;
  y: 14.5px;
  rx: 1px;
}

.oof2upb3i {
  cx: 12px;
  cy: 13px;
  r: 1.5px;
}

.szw-6_b5h {
  cx: 16px;
  cy: 13px;
  r: 1.5px;
}

.u-10n5mpy {
  cx: 8px;
  cy: 13px;
  r: 1.5px;
}

</style>
