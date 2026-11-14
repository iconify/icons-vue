<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jouf42b0n"/><path class="dqvg70bvr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ink-tank" /></template>
<style>
.dqvg70bvr {
  d: path("m12 12l2 3a2.25 2.25 0 1 1-4 0Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jouf42b0n {
  d: path("M9.75 2.5h4.5A1.75 1.75 0 0 1 16 4.25v.5a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 8 4.75v-.5A1.75 1.75 0 0 1 9.75 2.5m.25 4V9H6.5A2.5 2.5 0 0 0 4 11.5V19a2.5 2.5 0 0 0 2.5 2.5h11A2.5 2.5 0 0 0 20 19v-7.5A2.5 2.5 0 0 0 17.5 9H14V6.5");
}

</style>
