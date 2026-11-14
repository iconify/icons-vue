<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o22a6pnzw"/><path class="lm7t0abzv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hockey-scoreboard" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lm7t0abzv {
  d: path("M7 6.5h1A1.5 1.5 0 0 1 9.5 8v2A1.5 1.5 0 0 1 8 11.5H7A1.5 1.5 0 0 1 5.5 10V8A1.5 1.5 0 0 1 7 6.5m9 0h1A1.5 1.5 0 0 1 18.5 8v2a1.5 1.5 0 0 1-1.5 1.5h-1a1.5 1.5 0 0 1-1.5-1.5V8A1.5 1.5 0 0 1 16 6.5m-4 1.25h.01m-.01 2.5h.01");
}

.o22a6pnzw {
  d: path("M5.125 3.5h13.75A2.625 2.625 0 0 1 21.5 6.125v5.75a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 11.875v-5.75A2.625 2.625 0 0 1 5.125 3.5M5 14.5v7m14-7v7");
}

</style>
