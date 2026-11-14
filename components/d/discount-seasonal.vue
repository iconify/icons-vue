<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x58amxblz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:discount-seasonal" /></template>
<style>
.x58amxblz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.4 19.5H2.5V4H18v7.4M7 2.5v3m6.5-3v3m-11 3H18m-11 4h.01m3.74 0h.01M7 16h.01m9.49-1.75h5.25v7.5H16.5L13.75 18Zm.25 3.75h.01");
}

</style>
