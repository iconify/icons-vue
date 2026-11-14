<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7mxhu_kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:candy-wrapped" /></template>
<style>
.o7mxhu_kr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 12a5 4 0 1 0 10 0a5 4 0 1 0-10 0Zm0 0L2.5 8.5v7Zm10 0l4.5-3.5v7Zm-7-2.5l1.5 5");
}

</style>
