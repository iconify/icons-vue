<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obeow0d0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:banana-ripeness" /></template>
<style>
.obeow0d0f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 5c-1.5 6 1 13 8 15l.5-1.5c-5-2.5-6-8-5.5-13Zm1.5.25L5.25 2.5M15.5 3H21v18h-5.5Zm0 6H21m-5.5 6H21");
}

</style>
