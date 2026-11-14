<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy_3h_bqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:barcode-scanner-handheld" /></template>
<style>
.oy_3h_bqy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3.5h8.5a2.5 2.5 0 0 1 0 5H10l-1.5 8h-4l1.25-8H5a2.5 2.5 0 0 1 0-5Zm13.5 4l1 4m-5 3v7m3-7v7m3-7v7");
}

</style>
