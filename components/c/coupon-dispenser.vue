<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oy5j-acll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coupon-dispenser" /></template>
<style>
.oy5j-acll {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h19v3h-19Zm2.5 3h14v8H5Zm3 8v8h8v-8m-5.75 6.25l3.5-4M10.5 16h.01m2.99 3.5h.01m1.99-10h.01");
}

</style>
