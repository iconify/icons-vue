<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t269-otjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dimensioner" /></template>
<style>
.t269-otjf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.125 3h7.25A2.625 2.625 0 0 1 21 5.625v6.25a2.625 2.625 0 0 1-2.625 2.625h-7.25A2.625 2.625 0 0 1 8.5 11.875v-6.25A2.625 2.625 0 0 1 11.125 3m3.625 0v4M8.5 19H21m-10.75-1.75L8.5 19l1.75 1.75m9-3.5L21 19l-1.75 1.75M4 3v11.5M2.25 4.75L4 3l1.75 1.75m-3.5 8L4 14.5l1.75-1.75");
}

</style>
