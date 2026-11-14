<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tyh6er-mb"/><path class="nvuj68_ap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:action-figure" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nvuj68_ap {
  d: path("M9.5 9v5l-1 5m6-10v5l1 5m-8.75 0h10.5a1.25 1.25 0 0 1 1.25 1.25a1.25 1.25 0 0 1-1.25 1.25H6.75a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 6.75 19");
}

.tyh6er-mb {
  d: path("M10 4.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0M5 12.5L8 9h8l3 3.5");
}

</style>
