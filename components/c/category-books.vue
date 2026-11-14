<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aegs3ibzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:category-books" /></template>
<style>
.aegs3ibzh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3.5h14V9H6ZM3 9h15v6H3Zm1.5 6h17v6.5h-17Zm4-11.5V9M16 6.25h4M15.5 9v6M3 12h4m0 3v6.5m10.5-3.25h4");
}

</style>
