<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="izxss9b9e"/><rect class="rxb7_qbpa"/><rect class="cnpk1ubvp"/><path class="h_bgz6qri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:few-shot" /></template>
<style>
.cnpk1ubvp {
  width: 7px;
  height: 4.5px;
  x: 2.75px;
  y: 16.75px;
  rx: 1.5px;
}

.h_bgz6qri {
  d: path("M11.75 5c.9 0 1.25.4 1.25 1.25v4c0 1 .5 1.75 1.5 1.75c-1 0-1.5.75-1.5 1.75v4c0 .85-.35 1.25-1.25 1.25m6.5-10q.36 2.64 3 3q-2.64.36-3 3q-.36-2.64-3-3q2.64-.36 3-3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.izxss9b9e {
  width: 7px;
  height: 4.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.5px;
}

.rxb7_qbpa {
  width: 7px;
  height: 4.5px;
  x: 2.75px;
  y: 9.75px;
  rx: 1.5px;
}

</style>
