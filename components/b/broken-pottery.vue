<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_ry__sto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:broken-pottery" /></template>
<style>
.r_ry__sto {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 8l6-4.5L11.5 9L9 12l1.5 5L4 19Zm11-4.5L20.5 5L19 10.5l-3.5-1Zm0 10l5.5-.5l1.5 5.5l-4 2l-3.5-2.5Z");
}

</style>
