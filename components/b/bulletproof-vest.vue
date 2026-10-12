<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r3t3fob5j"/><rect class="eeyuvklfr"/><path class="pz__dzbwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bulletproof-vest" /></template>
<style>
.eeyuvklfr {
  width: 7.5px;
  height: 7px;
  x: 8.25px;
  y: 10px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pz__dzbwd {
  d: path("M3.75 13.5h1.5m13.5 0h1.5");
}

.r3t3fob5j {
  d: path("M8 2.75h.75q1 0 1.54.84l1.17 1.82q.54.84 1.08 0l1.17-1.82q.54-.84 1.54-.84H16q1 0 1.12.99l.26 2.27q.12.99.93 1.58l1.13.82q.81.59.81 1.59v8.25q0 1-.71 1.71l-.58.58q-.71.71-1.71.71H6.75q-1 0-1.71-.71l-.58-.58q-.71-.71-.71-1.71V10q0-1 .81-1.59l1.13-.82q.81-.59.93-1.58l.26-2.27Q7 2.75 8 2.75");
}

</style>
