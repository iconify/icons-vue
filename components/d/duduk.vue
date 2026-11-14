<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bfgytwdsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:duduk" /></template>
<style>
.bfgytwdsb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m20.132 3.868l-1.768 1.768m-1.591-1.591l3.182 3.182l-8.839 8.839l-1.944 5.126l-6.364-6.364l5.126-1.944Zm-.884 4.066h.01m-2.131 2.121h.01m-2.132 2.122h.01");
}

</style>
