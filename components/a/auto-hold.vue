<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wtuuug5-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:auto-hold" /></template>
<style>
.wtuuug5-h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 12a6 6 0 1 0 12 0a6 6 0 1 0-12 0Zm-.75 6.75a9.5 9.5 0 0 1 0-13.5m13.5 0a9.5 9.5 0 0 1 0 13.5m-8.25-9v4.5m3-4.5v4.5");
}

</style>
