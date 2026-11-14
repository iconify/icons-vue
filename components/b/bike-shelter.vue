<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ajhhk1b5k"/><path class="yn6xcrb2x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bike-shelter" /></template>
<style>
.ajhhk1b5k {
  d: path("M2.5 4.5h19M4 4.5v15m16-15v15m-13.25-2a2 2 0 1 0 4 0a2 2 0 1 0-4 0m6.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yn6xcrb2x {
  d: path("m8.75 17.5l2-3.5h3.5L12 17.5Zm5.5-3.5l1 3.5m-1-3.5l-.5-2");
}

</style>
