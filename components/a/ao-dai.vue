<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op_g48bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ao-dai" /></template>
<style>
.op_g48bom {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 4.25L7.5 5l-4 9.5h2l3-6l1 4.5l-1 8.5h7l-1-8.5l1-4.5l3 6h2l-4-9.5l-2.5-.75Zm.875-1.75h2.25a.875.875 0 0 1 .875.875a.875.875 0 0 1-.875.875h-2.25A.875.875 0 0 1 10 3.375a.875.875 0 0 1 .875-.875M9.5 13l-4 8m9-8l4 8");
}

</style>
