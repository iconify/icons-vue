<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tux-0cceq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:elt" /></template>
<style>
.tux-0cceq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 3.5H3v8h3.5M3 7.5h3m3.5-4v8H13m2-8h6m-3 0v8m-15 6h17.5m-3-3l3 3l-3 3");
}

</style>
