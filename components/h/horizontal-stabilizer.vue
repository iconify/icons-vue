<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lg5t_fj9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:horizontal-stabilizer" /></template>
<style>
.lg5t_fj9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.744 5.66l13.5 3.971a1.75 1.75 0 0 1 1.256 1.678v2.765a1.75 1.75 0 0 1-1.397 1.714l-13.5 2.779A1.75 1.75 0 0 1 3.5 16.853V7.339A1.75 1.75 0 0 1 5.744 5.66M3.5 14.75l17-2");
}

</style>
