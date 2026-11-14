<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgfrybcnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chisel" /></template>
<style>
.pgfrybcnl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m19.071 3.515l1.414 1.414a1.5 1.5 0 0 1 0 2.121l-3.535 3.536a1.5 1.5 0 0 1-2.122 0l-1.414-1.414a1.5 1.5 0 0 1 0-2.122l3.536-3.535a1.5 1.5 0 0 1 2.121 0m-6.364 7.778za3.25 3.25 0 0 1 0 4.596l-3.535 3.536a3.25 3.25 0 0 1-4.597 0a3.25 3.25 0 0 1 0-4.597l3.536-3.535a3.25 3.25 0 0 1 4.596 0m1.414-1.414l-1.414 1.414m3.536-7.071l3.535 3.535M8.464 10.939l4.597 4.597");
}

</style>
