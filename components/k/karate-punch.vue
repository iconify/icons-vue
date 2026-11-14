<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1nk69mjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:karate-punch" /></template>
<style>
.h1nk69mjs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm3 5.5H18m0-1.75h3.5v3.5H18ZM8.5 10l-1 5.5l-4 6m4-6L12 18v3.5");
}

</style>
