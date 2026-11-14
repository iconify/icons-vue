<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1lmrmbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bust-statue" /></template>
<style>
.c1lmrmbfl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 5.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-3 10c0-3 2.5-4.5 5.5-4.5s5.5 1.5 5.5 4.5Zm1.5 0h8l1.5 6h-11Z");
}

</style>
