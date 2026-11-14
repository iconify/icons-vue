<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vedqurbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-lakehouse" /></template>
<style>
.vedqurbnv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11L12 3l9.5 8m-16 2.5c1-1 2-1 3 0s2 1 3 0s2-1 3 0s2 1 3 0c.5-.5.75-.75 1-.75M5.5 17c1-1 2-1 3 0s2 1 3 0s2-1 3 0s2 1 3 0c.5-.5.75-.75 1-.75m-13 4.25c1-1 2-1 3 0s2 1 3 0s2-1 3 0s2 1 3 0c.5-.5.75-.75 1-.75");
}

</style>
