<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfd0lrhct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:football-american-location" /></template>
<style>
.qfd0lrhct {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 17.5C3 9 9 3 17.5 3c0 8.5-6 14.5-14.5 14.5m5.25-5.25l4-4m-4 2l2 2m0-4l2 2M18.5 21.5q-3-3-3-4.5a3 3 0 0 1 6 0q0 1.5-3 4.5");
}

</style>
