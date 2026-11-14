<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxd-56bpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:flood-house-water" /></template>
<style>
.pxd-56bpm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 12v-1.5L12 3.25l8.5 7.25V12m-18 3.75q2.25-2 4.75 0q2.25 2 4.75 0q2.25-2 4.75 0q2.25 2 4.75 0m-19 4.5q2.25-2 4.75 0q2.25 2 4.75 0q2.25-2 4.75 0q2.25 2 4.75 0");
}

</style>
