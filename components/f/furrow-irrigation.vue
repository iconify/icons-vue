<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3d3jmd1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:furrow-irrigation" /></template>
<style>
.n3d3jmd1u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4.5q9 5 18 0m-18 7q9 5 18 0m-18 7q9 5 18 0M8 3.5q1.25-.75 2.5 0t2.5 0t2.5 0m-7.5 7q1.25-.75 2.5 0t2.5 0t2.5 0m-7.5 7q1.25-.75 2.5 0t2.5 0t2.5 0");
}

</style>
