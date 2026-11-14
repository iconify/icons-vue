<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4jrl1btl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-computer-accessories" /></template>
<style>
.h4jrl1btl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3.5h4a3 3 0 0 1 3 3v9a3 3 0 0 1-3 3h-4a3 3 0 0 1-3-3v-9a3 3 0 0 1 3-3Zm2 0V10m-5 0h10");
}

</style>
