<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxhzn9bwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:atis" /></template>
<style>
.nxhzn9bwi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 7.5h2a3.5 3.5 0 0 1 3.5 3.5v7a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 18v-7A3.5 3.5 0 0 1 8 7.5m-.5 0v-5m0 14h3m5.873-7.91a3.75 3.75 0 0 1 0 4.82m2.298-6.749a6.75 6.75 0 0 1 0 8.678");
}

</style>
