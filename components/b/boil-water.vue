<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf-nb8e1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:boil-water" /></template>
<style>
.yf-nb8e1x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9h18M5 9v7a2.5 2.5 0 0 0 2.5 2.5h9A2.5 2.5 0 0 0 19 16V9M7 21.5h10M9.5 6.25q-1-1 0-2t0-2m5 4q-1-1 0-2t0-2");
}

</style>
