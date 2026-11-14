<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x1b0b7btb"/><path class="t0gleco6l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crystal-oscillator" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t0gleco6l {
  d: path("M12 8.5za1.5 1.5 0 0 1 1.5 1.5v4a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5v-4A1.5 1.5 0 0 1 12 8.5m-5.5 0v7m11-7v7");
}

.x1b0b7btb {
  d: path("M9.75 6h4.5A1.75 1.75 0 0 1 16 7.75v8.5A1.75 1.75 0 0 1 14.25 18h-4.5A1.75 1.75 0 0 1 8 16.25v-8.5A1.75 1.75 0 0 1 9.75 6M3 12h3.5m11 0H21");
}

</style>
