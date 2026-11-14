<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gryblnb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:grocery-delivery-crate" /></template>
<style>
.gryblnb1y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.493 10h15.014a1.75 1.75 0 0 1 1.735 1.976l-1.043 8a1.75 1.75 0 0 1-1.736 1.524H5.537a1.75 1.75 0 0 1-1.736-1.524l-1.043-8A1.75 1.75 0 0 1 4.493 10M9.5 10V7.5c0-1 1.25-1.5 1.25-2.5V2.5h2.5V5c0 1 1.25 1.5 1.25 2.5V10m-8.75 3.5h3m6.5 0h3");
}

</style>
