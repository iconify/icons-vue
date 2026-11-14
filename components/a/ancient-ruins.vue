<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad71g3bid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ancient-ruins" /></template>
<style>
.ad71g3bid {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 21V6h-1V3.5h8V6h-1v15m3 0v-9l1.5-1.5l1.25 1.5l1.25-2.5l1 1.5v10m-17 0h19");
}

</style>
