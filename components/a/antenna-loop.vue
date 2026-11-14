<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nn3xdxbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:antenna-loop" /></template>
<style>
.nn3xdxbfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 14.75a5.5 5.5 0 1 1 3 0m-3 0l1.5 2l1.5-2m-1.5 2v4.75m-3.5 0h7m3.5-17a8.5 8.5 0 0 1 1.25 7.25");
}

</style>
