<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6p2dd05j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cam-mechanism" /></template>
<style>
.l6p2dd05j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.5 15c0 2.5-5 5.5-9.5 5.5c-3.5 0-5.5-2.5-5.5-5.5s2-5.5 5.5-5.5c4.5 0 9.5 3 9.5 5.5ZM10 2.5v7m-2.25 0h4.5M10 15h.01");
}

</style>
