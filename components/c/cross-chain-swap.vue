<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wk9zh5bve"/><path class="a6vuw1bfi"/><path class="nqc96ob1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cross-chain-swap" /></template>
<style>
.a6vuw1bfi {
  d: path("M17.25 8.75L19 10.5l1.75-1.75M10.5 19C7 19 5 17 5 13.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nqc96ob1s {
  d: path("M3.25 15.25L5 13.5l1.75 1.75");
}

.wk9zh5bve {
  d: path("M3.5 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m9 9a4 4 0 1 0 8 0a4 4 0 1 0-8 0m1-11.5C17 5 19 7 19 10.5");
}

</style>
