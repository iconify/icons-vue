<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4k_frb-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:buoy-boundary" /></template>
<style>
.g4k_frb-k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 15.5a6 6 0 0 1 12 0ZM12 3v6.5m1.603-5.799l.397.174a.955.955 0 0 1 0 1.75l-.397.174A1.145 1.145 0 0 1 12 4.75a1.145 1.145 0 0 1 1.603-1.049M3 19.5q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
