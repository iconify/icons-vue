<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6tn3l1yr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:american-football-hike" /></template>
<style>
.x6tn3l1yr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8.75c3-6 15-6 18 0c-3 6-15 6-18 0m-.5 4.5h19m-12-4.5h5M10.75 7.5V10m2.5-2.5V10m2.25 7.75h-7M10.25 16L8.5 17.75l1.75 1.75");
}

</style>
