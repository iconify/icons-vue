<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nvmc45cpa"/><path class="tndrgcbrg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:battery-train" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nvmc45cpa {
  d: path("M8.25 2.5h.5A5.25 5.25 0 0 1 14 7.75v3.5a5.25 5.25 0 0 1-5.25 5.25h-.5A5.25 5.25 0 0 1 3 11.25v-3.5A5.25 5.25 0 0 1 8.25 2.5");
}

.tndrgcbrg {
  d: path("M7.75 5.5h1.5A1.75 1.75 0 0 1 11 7.25A1.75 1.75 0 0 1 9.25 9h-1.5A1.75 1.75 0 0 1 6 7.25A1.75 1.75 0 0 1 7.75 5.5M6.5 12h.01m3.99 0h.01M6.5 16.5L5 20m5.5-3.5L12 20m4.5-3h3a1 1 0 0 1 1 1v.5h1V20h-1v.5a1 1 0 0 1-1 1h-3a1 1 0 0 1-1-1V18a1 1 0 0 1 1-1");
}

</style>
