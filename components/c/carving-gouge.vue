<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hs8z303_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:carving-gouge" /></template>
<style>
.hs8z303_j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.646 8.818l3.536 3.536l-7.778 7.778l-3.536-3.536Zm4.597-1.061l-2.829 2.829m7.071-2.829a3 3 0 0 1-4.242-4.242");
}

</style>
