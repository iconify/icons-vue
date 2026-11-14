<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-cxduhjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gift-option" /></template>
<style>
.h-cxduhjb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8h12v4H3Zm1.5 4v5.5q0 3 3 3h3q1.427 0 2.175-.679m.825-4.534V12M9 8v12.5M9 8C8 4.5 5 3.5 5 5.25S7.5 8 9 8Zm0 0c1-3.5 4-4.5 4-2.75S10.5 8 9 8Zm5.75 10l2 2L21 15.75");
}

</style>
