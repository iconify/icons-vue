<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dor8g8b6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heart-tap" /></template>
<style>
.dor8g8b6t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 21c-4-3-7-5.5-7-8.5a3.75 3.75 0 0 1 7-1a3.75 3.75 0 0 1 7 1c0 3-3 5.5-7 8.5m5.065-16.048a7.5 7.5 0 0 1 4.483 4.483M17.75 2.907a10.5 10.5 0 0 1 3.843 3.843");
}

</style>
