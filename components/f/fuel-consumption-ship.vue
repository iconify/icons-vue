<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4o-42nfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fuel-consumption-ship" /></template>
<style>
.r4o-42nfp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.442 16.5H5L2.5 11h19l-.662 1.457M6 7h4.5A1.5 1.5 0 0 1 12 8.5v1a1.5 1.5 0 0 1-1.5 1.5H6a1.5 1.5 0 0 1-1.5-1.5v-1A1.5 1.5 0 0 1 6 7m10.5-3H18a1.5 1.5 0 0 1 1.5 1.5v4A1.5 1.5 0 0 1 18 11h-1.5A1.5 1.5 0 0 1 15 9.5v-4A1.5 1.5 0 0 1 16.5 4m2 10s2.75 3 2.75 5a2.75 2.75 0 0 1-5.5 0c0-2 2.75-5 2.75-5");
}

</style>
