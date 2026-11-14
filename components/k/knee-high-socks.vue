<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l09idrr-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:knee-high-socks" /></template>
<style>
.l09idrr-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 2.5h5v16a3 3 0 0 1-3 3h-3a2 2 0 0 1-2-2a2 2 0 0 1 2-2h1Zm13 0h-5v16a3 3 0 0 0 3 3h3a2 2 0 0 0 2-2a2 2 0 0 0-2-2h-1ZM5.5 6h5m3 0h5");
}

</style>
