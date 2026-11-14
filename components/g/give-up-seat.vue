<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpsredcdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:give-up-seat" /></template>
<style>
.cpsredcdl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m19.5 3.5l-1 10.5h-7m3.5 0v6.5m-3.5 0h7M4 7.5h1A1.5 1.5 0 0 0 6.5 6a.621.621 0 0 1 1.061-.439l2.878 2.878a1.5 1.5 0 0 1 0 2.122l-2.878 2.878A.621.621 0 0 1 6.5 13A1.5 1.5 0 0 0 5 11.5H4A1.5 1.5 0 0 1 2.5 10V9A1.5 1.5 0 0 1 4 7.5");
}

</style>
