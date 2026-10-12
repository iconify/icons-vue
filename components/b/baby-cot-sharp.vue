<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgoim5ubr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baby-cot-sharp" /></template>
<style>
.dgoim5ubr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 12v-1.5a6 6 0 0 1 6-6h.5V12Zm0 0h15v6h-15v-4.5ZM11 8.75h8.5M9 18l-2 2.25M15 18l2 2.25m-13-.5c5 1.5 11 1.5 16 0");
}

</style>
