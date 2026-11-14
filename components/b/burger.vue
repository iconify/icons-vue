<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xj8pv7b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:burger" /></template>
<style>
.xj8pv7b2j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 10.5C3.5 6.5 7.25 4 12 4s8.5 2.5 8.5 6.5Zm0 6h17V20h-17Zm0-3q2.5 2 5 0t5 0t7 0");
}

</style>
