<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpjlfccjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:beach-venue" /></template>
<style>
.kpjlfccjf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10a7.5 7 0 0 1 15 0Zm7.5 0v10m0-17l-3.25 7M10 3l3.25 7M3 20h9.5m3-.5q1.5-1.5 3 0t3 0");
}

</style>
