<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zahzn5j8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crocodile-head" /></template>
<style>
.zahzn5j8l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 12V7a3 3 0 0 1 6 0h5a3 3 0 0 1 6 0v5H18l-1.25 2.25L15.5 12h-2.25L12 14.25L10.75 12H8.5l-1.25 2.25L6 12Zm1 5h15c-.5 2.5-2.5 3-7.5 3s-7-.5-7.5-3Zm2-10h.01M17.5 7h.01");
}

</style>
