<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9796gbpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:baby-food-pouch" /></template>
<style>
.e9796gbpc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.817 7.5h4.366a2.625 2.625 0 0 1 2.604 2.299l1.094 8.75a2.625 2.625 0 0 1-2.605 2.951H8.724a2.625 2.625 0 0 1-2.605-2.951l1.094-8.75A2.625 2.625 0 0 1 9.817 7.5M14.25 3h1A1.75 1.75 0 0 1 17 4.75v1a1.75 1.75 0 0 1-1.75 1.75h-1a1.75 1.75 0 0 1-1.75-1.75v-1A1.75 1.75 0 0 1 14.25 3m-8 14.5h11.5");
}

</style>
