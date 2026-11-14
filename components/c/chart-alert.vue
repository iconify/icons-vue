<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o2csh_b0k"/><path class="fxtoacb0p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chart-alert" /></template>
<style>
.fxtoacb0p {
  d: path("M6.5 14L10 8.5l3 2.5l6-6.5m.324 11.982l1.5 2.812A1.5 1.5 0 0 1 19.5 21.5h-3a1.5 1.5 0 0 1-1.324-2.206l1.5-2.812a1.5 1.5 0 0 1 2.648 0M18 17.25v1M18 20h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o2csh_b0k {
  d: path("M3.5 3v17.5h8.7");
}

</style>
