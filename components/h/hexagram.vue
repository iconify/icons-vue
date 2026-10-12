<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i-d3j041c"/><path class="yyqcq0b4h"/><circle class="h_tsn8bxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hexagram" /></template>
<style>
.h_tsn8bxt {
  cx: 12px;
  cy: 12px;
  r: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i-d3j041c {
  d: path("m12.63 3.58l6.97 12.09q.63 1.08-.62 1.08H5.02q-1.25 0-.62-1.08l6.98-12.09q.62-1.08 1.25 0");
}

.yyqcq0b4h {
  d: path("M11.38 20.42L4.4 8.33q-.63-1.08.62-1.08h13.96q1.25 0 .62 1.08l-6.97 12.09q-.63 1.08-1.25 0");
}

</style>
