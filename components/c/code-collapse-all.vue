<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jajvgv8ww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:code-collapse-all" /></template>
<style>
.jajvgv8ww {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 6.5L12 3l5 3.5M7 10l5-3.5l5 3.5m-8.5 3.5l-4 3.75l4 3.75m7-7.5l4 3.75l-4 3.75");
}

</style>
