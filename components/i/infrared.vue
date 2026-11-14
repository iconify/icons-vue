<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1950cb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:infrared" /></template>
<style>
.z1950cb0q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 15V8.5a3.5 3.5 0 0 1 7 0V15Zm2 0v5m3-5v5m5-13.5q1.5-2 3 0t3 0q1.25-1.75 2.5 0M13 12q1.5-2 3 0t3 0q1.25-1.75 2.5 0M13 17.5q1.5-2 3 0t3 0q1.25-1.75 2.5 0");
}

</style>
