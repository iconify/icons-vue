<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih_ct4d3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dog-treat" /></template>
<style>
.ih_ct4d3y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 10h9a2.25 2.25 0 1 1 3 2a2.25 2.25 0 1 1-3 2h-9a2.25 2.25 0 1 1-3-2a2.25 2.25 0 1 1 3-2Zm3 2h.01m2.99 0h.01");
}

</style>
