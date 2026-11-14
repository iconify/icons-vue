<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aqq3udigm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:candle-hazard" /></template>
<style>
.aqq3udigm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 11.5h4.5A1.75 1.75 0 0 1 12 13.25v6.5a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 4 19.75v-6.5a1.75 1.75 0 0 1 1.75-1.75M8 2.5c1.75 1.75 2.5 2.75 2.5 4a2.5 2.5 0 0 1-5 0c0-1.25.75-2.25 2.5-4M8 9v2.5m10 3V18m0 3h.01");
}

</style>
