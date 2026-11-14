<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yldz57buk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:grocery-delivery-crate" /></template>
<style>
.yldz57buk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10h19L20 21.5H4Zm7 0V7.5c0-1 1.25-1.5 1.25-2.5V2.5h2.5V5c0 1 1.25 1.5 1.25 2.5V10m-8.75 3.5h3m6.5 0h3");
}

</style>
