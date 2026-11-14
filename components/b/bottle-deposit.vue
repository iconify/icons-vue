<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqgbq7tew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bottle-deposit" /></template>
<style>
.zqgbq7tew {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5h3V6l2 3v10.5A1.5 1.5 0 0 1 10 21H6a1.5 1.5 0 0 1-1.5-1.5V9l2-3ZM15 16a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm3-1.25v2.5");
}

</style>
