<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m9-3abb0t"/><path class="tk-nsf1dw"/><path class="kbuscdb_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flower-garland" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kbuscdb_g {
  d: path("M6.25 15q-2.75.25-2.75 3.25Q6.25 18 6.25 15m11.5 0q2.75.25 2.75 3.25Q17.75 18 17.75 15");
}

.m9-3abb0t {
  d: path("M4 6.5a1.5 1.5 0 0 1 3 0a1.5 1.5 0 0 1 0 3a1.5 1.5 0 0 1-3 0a1.5 1.5 0 0 1 0-3m6.5 8.5a1.5 1.5 0 0 1 3 0a1.5 1.5 0 0 1 0 3a1.5 1.5 0 0 1-3 0a1.5 1.5 0 0 1 0-3M17 6.5a1.5 1.5 0 0 1 3 0a1.5 1.5 0 0 1 0 3a1.5 1.5 0 0 1-3 0a1.5 1.5 0 0 1 0-3");
}

.tk-nsf1dw {
  d: path("M5.5 11q0 5.5 3.5 5.5m6 0q3.5 0 3.5-5.5");
}

</style>
