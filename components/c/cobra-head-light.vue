<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hv-h0ubuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cobra-head-light" /></template>
<style>
.hv-h0ubuo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 21.5V7a3.5 3.5 0 0 1 3.5-3.5H11m0 0h6c2 0 2.5 1.5 2.5 2.25c0 1-1 1.75-2.5 1.75h-4.5L11 6Zm1 6.75L9 17.5m9-7.25l3 7.25");
}

</style>
