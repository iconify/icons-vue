<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5o1s-b4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bin-on-post" /></template>
<style>
.c5o1s-b4r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 6h16M9.5 6V4.5a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1V6m-9 0l1 9A1.5 1.5 0 0 0 8 16.5h8a1.5 1.5 0 0 0 1.5-1.5l1-9M10 9v4.5M14 9v4.5m-2 3v5m-3.5 0h7");
}

</style>
