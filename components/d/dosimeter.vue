<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ygxwhgbta"/><path class="tyzfstkvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dosimeter" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tyzfstkvr {
  d: path("M7.5 15.5a4.5 4.5 0 0 1 9 0m-4.5 0l2.5-3.25");
}

.ygxwhgbta {
  d: path("M8.5 5h7A3.5 3.5 0 0 1 19 8.5V18a3.5 3.5 0 0 1-3.5 3.5h-7A3.5 3.5 0 0 1 5 18V8.5A3.5 3.5 0 0 1 8.5 5m1 0V2.5h5V5");
}

</style>
