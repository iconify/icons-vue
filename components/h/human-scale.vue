<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yagj5wbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:human-scale" /></template>
<style>
.yagj5wbxl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM9 8v6.5M6.5 21L9 14.5l2.5 6.5M17 3v18M6 10.5l3-1.75l3 1.75M15.5 3h3m-3 18h3");
}

</style>
