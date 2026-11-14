<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t5lbvybth"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deal-closing-soon" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

.t5lbvybth {
  d: path("M3 2.5h11.5M3 21.5h9.4M5 2.5c0 6 2.25 8 2.25 9.5S5 15.5 5 21.5m7.5-19c0 6-2.25 8-2.25 9.5c0 .874.764 1.919 1.402 3.826M6.25 21.5q2.5-5.5 5 0M14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
