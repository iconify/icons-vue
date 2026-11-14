<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ayvnk-btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ad-audience" /></template>
<style>
.ayvnk-btb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 8a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-3 12c0-4 2.5-6 6-6c1.503 0 2.822.369 3.838 1.107M14 6.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm.5 11.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm3.5 0h.01");
}

</style>
