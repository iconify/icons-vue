<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n2wspok0t"/><path class="rrbiej30t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dhol-drum" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n2wspok0t {
  d: path("M5 11q7-1.5 14 0a2 4.75 0 0 1 0 9.5q-7 1.5-14 0");
}

.rrbiej30t {
  d: path("M3 15.75a2 4.75 0 1 0 4 0a2 4.75 0 1 0-4 0m5.5-5.25L11 21l2.5-10.75L16 21M6 7l11-4.5M18 7L7 2.5");
}

</style>
