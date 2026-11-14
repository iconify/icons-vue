<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h17_-bcle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chinos" /></template>
<style>
.h17_-bcle {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.5h12v3l.5 16h-5L12 9l-1.5 12.5h-5l.5-16Zm0 3h12m-9.75 3L8 21.5m7.75-13l.25 13");
}

</style>
