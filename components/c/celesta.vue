<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k17xqot3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:celesta" /></template>
<style>
.k17xqot3r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 16V9C3.5 5 7 3 12 3s8.5 2 8.5 6v7Zm0-4h17m-15 4v5.5m13-5.5v5.5M9.25 12v4m5.5-4v4");
}

</style>
