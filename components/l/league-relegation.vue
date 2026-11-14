<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z42jgmbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:league-relegation" /></template>
<style>
.z42jgmbic {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3h10v5.5a5 5 0 0 1-10 0Zm0 2H4.5a2 2 0 0 0 0 4H6m10-4h1.5a2 2 0 0 1 0 4H16m-5 4.5V19m-2.5 0h3.7m5.8-4.5v7m-3-3l3 3l3-3");
}

</style>
