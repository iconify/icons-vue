<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dq_xsvy1y"/><path class="m59hf2bey"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lawn-mower" /></template>
<style>
.dq_xsvy1y {
  d: path("M10.5 11H19a2.5 2.5 0 0 1 2.5 2.5A2.5 2.5 0 0 1 19 16h-8.5A2.5 2.5 0 0 1 8 13.5a2.5 2.5 0 0 1 2.5-2.5m-1 0L5 4H2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m59hf2bey {
  d: path("M9.25 18a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
