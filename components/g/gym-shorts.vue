<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1-dw6bit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gym-shorts" /></template>
<style>
.w1-dw6bit {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 5h16v3.5L21.5 19h-8L12 13.5L10.5 19h-8L4 8.5Zm0 3.5h16m-2.75 0l1.5 10.5");
}

</style>
