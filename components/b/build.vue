<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt7nmsbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:build" /></template>
<style>
.pt7nmsbov {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.055 2.873l7.072 7.072l-3.182 3.182l-7.072-7.072ZM12.5 9.5L3 19m9.5-3H21v5.5h-8.5Z");
}

</style>
