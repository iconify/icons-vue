<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ro72bob6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:flood-house-water" /></template>
<style>
.ro72bob6t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 12v-1.5L12 3.25l8.5 7.25V12m-18 3.75q2.25-2 4.75 0q2.25 2 4.75 0q2.25-2 4.75 0q2.25 2 4.75 0m-19 4.5q2.25-2 4.75 0q2.25 2 4.75 0q2.25-2 4.75 0q2.25 2 4.75 0");
}

</style>
