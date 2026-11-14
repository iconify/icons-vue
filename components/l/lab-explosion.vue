<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="du4bdtbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lab-explosion" /></template>
<style>
.du4bdtbzn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 9v3l-5 7a1.5 1.5 0 0 0 1.25 2h11.5A1.5 1.5 0 0 0 19 19l-5-7V9M9 9h6m-3-6.5v3.25M6.5 4l1.75 2.25M17.5 4l-1.75 2.25");
}

</style>
