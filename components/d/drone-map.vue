<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wor92w38s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drone-map" /></template>
<style>
.wor92w38s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 5.5h5V9h-5Zm0 1.75H5V3.5m9.5 3.75H19V3.5m-16.5 0h5m9 0h5M5 13.25l4.5-1.5l5 1.5l4.5-1.5v7l-4.5 1.5l-5-1.5l-4.5 1.5Zm4.5-1.5v7m5-5.5v7");
}

</style>
