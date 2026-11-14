<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba55eq38z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:golf-birdie" /></template>
<style>
.ba55eq38z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 8.5q3.25-5.5 6.75 0q3.5-5.5 6.75 0M3 17.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m7.5-3.75q2-1.75 5-2.25");
}

</style>
