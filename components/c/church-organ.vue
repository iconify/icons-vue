<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m087n0baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:church-organ" /></template>
<style>
.m087n0baw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 15V9H7V6h3.5V3h3v3H17v3h3.5v6M7 15V9m3.5 6V6m3 9V6m3.5 9V9M5.125 15h13.75a2.625 2.625 0 0 1 2.625 2.625v1.25a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 18.875v-1.25A2.625 2.625 0 0 1 5.125 15M2.5 18.25h19m-13 0v3.25m7-3.25v3.25");
}

</style>
