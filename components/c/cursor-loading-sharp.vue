<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sryxigj5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cursor-loading-sharp" /></template>
<style>
.sryxigj5x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.9 4.24l9.95 4.27L17 9l-1.19.38l-3.12.99l-1.19.38l-.44 1.17l-1.37 3.66l-.44 1.17l-.41-1.18L5.16 4.93l-.41-1.18zm11.35 9.51a3.5 3.5 0 1 1-3.5 3.5");
}

</style>
