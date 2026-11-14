<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4y-0ui3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coffee-mug" /></template>
<style>
.y4y-0ui3v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4.5H16v12a4 4 0 0 1-4 4H7.5a4 4 0 0 1-4-4Zm12.5 3h1a3.5 3.5 0 0 1 0 7h-1");
}

</style>
