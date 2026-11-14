<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twyqr5bcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:climate-risk-gauge" /></template>
<style>
.twyqr5bcf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 13.5a9 9 0 0 1 18 0M7.5 5.75L9 8.25m7.5-2.5L15 8.25m-3 5.25l5.25-3m-5.25 3h.01M18 14.75v3.5M18 21h.01");
}

</style>
