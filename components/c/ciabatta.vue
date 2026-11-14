<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d06luozdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ciabatta" /></template>
<style>
.d06luozdt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 17h15c2 0 2.5-1.5 2-3.5C20.5 9.5 17 7 12 7s-8.5 2.5-9.5 6.5c-.5 2 0 3.5 2 3.5Zm4-2.5l1.5-3.25m3.5 3.25l1.5-3.25");
}

</style>
