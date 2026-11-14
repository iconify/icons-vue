<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yd1nd_blt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leaf-single-fall" /></template>
<style>
.yd1nd_blt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 10c6 0 10.5 4.5 10.5 10.5C14.5 20.5 10 16 10 10Zm0 0L8 8m2 2l6 6M2.75 11Q4.5 3 13 3.5");
}

</style>
