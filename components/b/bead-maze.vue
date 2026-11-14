<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yssyf8lqd"/><path class="chlh2bctx"/><path class="kjgq6hc5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bead-maze" /></template>
<style>
.chlh2bctx {
  d: path("M2.5 14.75h4.75L12 9.25l4.75 5.5h4.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kjgq6hc5u {
  d: path("M5.25 14.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0M10 9.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0m4.75 5.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

.yssyf8lqd {
  d: path("M6.875 4.5h10.25A4.375 4.375 0 0 1 21.5 8.875v6.25a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 15.125v-6.25A4.375 4.375 0 0 1 6.875 4.5");
}

</style>
