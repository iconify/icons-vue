<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wsnlo4o1j"/><path class="a6vuw1bfi"/><path class="nqc96ob1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cross-chain-swap" /></template>
<style>
.a6vuw1bfi {
  d: path("M17.25 8.75L19 10.5l1.75-1.75M10.5 19C7 19 5 17 5 13.5");
}

.nqc96ob1s {
  d: path("M3.25 15.25L5 13.5l1.75 1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wsnlo4o1j {
  d: path("M3.5 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm9 9a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm1-11.5C17 5 19 7 19 10.5");
}

</style>
