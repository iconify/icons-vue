<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-o3qlbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lighthouse-screwpile" /></template>
<style>
.u-o3qlbrb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 6L12 2.5L16.5 6ZM9 6h6v4.5H9Zm-3 4.5h12m-11 0l-2.5 10m12.5-10l2.5 10M6 14.5h12M3 8.25h2.5m13 0H21M3 20.5q2.25-1.25 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
