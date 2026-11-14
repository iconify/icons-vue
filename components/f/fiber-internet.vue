<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1vhidc8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fiber-internet" /></template>
<style>
.c1vhidc8l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5C2.5 17 4.5 15 8 15m0-2.5h5v5H8Zm5 2.5h1.25m2.25 0h5m-5.25-2.25l3.75-3m-3.75 7.5l3.75 3");
}

</style>
