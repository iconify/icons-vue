<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gwas7katj"/><path class="qvaeq0cby"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:campervan" /></template>
<style>
.gwas7katj {
  d: path("M2.5 17V9a2 2 0 0 1 2-2H16l5.5 5.5V17Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qvaeq0cby {
  d: path("M5 18.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M7 10h2a1.5 1.5 0 0 1 1.5 1.5v.5A1.5 1.5 0 0 1 9 13.5H7A1.5 1.5 0 0 1 5.5 12v-.5A1.5 1.5 0 0 1 7 10");
}

</style>
