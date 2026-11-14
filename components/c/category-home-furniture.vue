<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ot2sk4bsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-home-furniture" /></template>
<style>
.ot2sk4bsv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 12V9a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v3M3 12h18v5H3Zm2 5v3m14-3v3");
}

</style>
