<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eb24dcbjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:decibel" /></template>
<style>
.eb24dcbjf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9.75H5L8 6.5v11l-3-3.25H2.5ZM10.75 18v-2.5M13.5 18v-5m2.75 5v-7.5M19 18V8m2.75 10V5.5");
}

</style>
