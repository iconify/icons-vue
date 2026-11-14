<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0uj2wtip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:atp-molecule" /></template>
<style>
.w0uj2wtip {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.5 12l-1.75 3h-3.5L2.5 12l1.75-3h3.5Zm0 0h1a1.5 1.5 0 1 1 3 0a1.5 1.5 0 1 1-3 0m3 0h1a1.5 1.5 0 1 1 3 0a1.5 1.5 0 1 1-3 0m3 0h1a1.5 1.5 0 1 1 3 0a1.5 1.5 0 1 1-3 0");
}

</style>
