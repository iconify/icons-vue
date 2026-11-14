<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yes4i0eek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:breakfast-bar" /></template>
<style>
.yes4i0eek {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6h19v2.5h-19ZM4 8.5v13m16-13v13m-12.75-8a2 1 0 1 0 4 0a2 1 0 1 0-4 0Zm2 1v7m-1.5 0h3m2-8a2 1 0 1 0 4 0a2 1 0 1 0-4 0Zm2 1v7m-1.5 0h3");
}

</style>
