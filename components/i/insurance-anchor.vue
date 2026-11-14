<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qaz8xslms"/><path class="e0smqgaxp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:insurance-anchor" /></template>
<style>
.e0smqgaxp {
  d: path("m3 15l1.5-1.5L6 15m12 0l1.5-1.5L21 15");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qaz8xslms {
  d: path("M10 4.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2 2V21m-7.5-7.5C4.5 17.75 8 21 12 21s7.5-3.25 7.5-7.5m-11-3.25h7");
}

</style>
