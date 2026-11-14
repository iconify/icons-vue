<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi-39zl3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crowdfunding-stretch-goal" /></template>
<style>
.fi-39zl3k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 11.5h6A2.75 2.75 0 0 1 14 14.25A2.75 2.75 0 0 1 11.25 17h-6a2.75 2.75 0 0 1-2.75-2.75a2.75 2.75 0 0 1 2.75-2.75M17 3.5v17m0-17h4l-1.5 2.75L21 9h-4M5.25 14.25h6");
}

</style>
