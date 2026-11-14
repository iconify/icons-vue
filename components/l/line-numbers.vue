<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyj4ulb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:line-numbers" /></template>
<style>
.zyj4ulb8j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4.5L5 3v6.5M3 14a2 2 0 1 1 3.5 1.5l-3.5 5h4m2.5-18v19m3-16h8m-8 6.5h6m-6 6.5H20");
}

</style>
