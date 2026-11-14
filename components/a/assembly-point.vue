<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4elvos1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:assembly-point" /></template>
<style>
.t4elvos1o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 12a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm3-8.5V6M9.5 5L12 3.5L14.5 5m-11 7H6M5 9.5L3.5 12L5 14.5M20.5 12H18m1-2.5l1.5 2.5l-1.5 2.5m-7 6V18m-2.5 1l2.5 1.5l2.5-1.5");
}

</style>
