<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8ehs1b8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:energy-law" /></template>
<style>
.v8ehs1b8z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 6.5h13m-6.5-3v17m-2.5 0h5m1-7l3-7l3 7Zm0 0a3 3 0 0 0 6 0m-16-7L9 13H5.5L7 19l-4.5-8.5H6Z");
}

</style>
