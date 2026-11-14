<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2ha0z12v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:diving-platform" /></template>
<style>
.x2ha0z12v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 20.5V5A1.5 1.5 0 0 1 5 3.5h2A1.5 1.5 0 0 1 8.5 5v15.5m0-14H19m-16.5 14h19m-10-5q2.5-2 5 0t5 0");
}

</style>
