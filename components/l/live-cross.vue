<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nj42gcc-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:live-cross" /></template>
<style>
.nj42gcc-r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.5 9.5l5 5m0-5l-5 5M7.822 7.021a6.5 6.5 0 0 1 8.356 0m0 9.958a6.5 6.5 0 0 1-8.356 0M5.894 4.723a9.5 9.5 0 0 1 12.212 0m0 14.554a9.5 9.5 0 0 1-12.212 0");
}

</style>
