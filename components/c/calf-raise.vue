<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3c5ehq-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:calf-raise" /></template>
<style>
.c3c5ehq-r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 2.5V13l3 6l4 2.5h3.5l-1-1.5l-3.5-2.5l-1-4.5V2.5m-8 18v-6m-1 1za1.414 1.414 0 0 1 2 0a.586.586 0 0 1-.414 1H5.664a.586.586 0 0 1-.414-1");
}

</style>
