<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j97_f306a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-trendline" /></template>
<style>
.j97_f306a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11L7 5.5l4.5 4L16 4l5.5 3.5M3 21l1.75-1M7 18.75l1.75-1M11 16.5l1.75-1M15 14.25l1.75-1m1.5-.75l1.75-1m-2.5-.25l2.5.25l-1 2.25");
}

</style>
