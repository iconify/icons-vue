<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krw7hzbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:freestanding-bathtub" /></template>
<style>
.krw7hzbgj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 11h16v2a6 6 0 0 1-6 6h-4a6 6 0 0 1-6-6Zm4 8.5L7 21m9-1.5l1 1.5m2-10V6a2 2 0 0 0-4 0");
}

</style>
