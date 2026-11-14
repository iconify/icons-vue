<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a3w_d9vpc"/><path class="wxrza7yvt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:beanie-pompom" /></template>
<style>
.a3w_d9vpc {
  d: path("M5.5 16c0-5.5 2.5-8.25 6.5-8.25s6.5 2.75 6.5 8.25M6 16h12a2.5 2.5 0 0 1 2.5 2.5A2.5 2.5 0 0 1 18 21H6a2.5 2.5 0 0 1-2.5-2.5A2.5 2.5 0 0 1 6 16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wxrza7yvt {
  d: path("M9.75 5.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M8.25 16v5M12 16v5m3.75-5v5");
}

</style>
