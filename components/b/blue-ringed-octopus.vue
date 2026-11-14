<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cocqj-htp"/><path class="w5-x7bw7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blue-ringed-octopus" /></template>
<style>
.cocqj-htp {
  d: path("M4.5 9a7.5 6.5 0 1 0 15 0a7.5 6.5 0 1 0-15 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w5-x7bw7c {
  d: path("M7 13.75Q6 19 2.5 18.5m8-3.25Q11 20 8 21.5m5.5-6.25Q13 20 16 21.5m1-7.75q1 5.25 4.5 4.75M7.25 8.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m6 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
