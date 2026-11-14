<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kebju1mox"/><path class="awzy1dxlv"/><path class="utb86dbay"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:liquify" /></template>
<style>
.awzy1dxlv {
  d: path("M9 3c0 4.5-2.5 5.5-2.5 9S9 16.5 9 21m6-18c0 4.5 2.5 5.5 2.5 9S15 16.5 15 21");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kebju1mox {
  d: path("M7.375 3h9.25A4.375 4.375 0 0 1 21 7.375v9.25A4.375 4.375 0 0 1 16.625 21h-9.25A4.375 4.375 0 0 1 3 16.625v-9.25A4.375 4.375 0 0 1 7.375 3");
}

.utb86dbay {
  d: path("M3 9c4.5 0 5.5-2.5 9-2.5S16.5 9 21 9M3 15c4.5 0 5.5 2.5 9 2.5s4.5-2.5 9-2.5m-11-3a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
