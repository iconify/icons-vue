<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg81i5glq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fried-chicken-shop" /></template>
<style>
.eg81i5glq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 14.75C7 10 9.5 3 15.5 3c4 0 6 2.5 5.5 6c-.5 5-7 7.5-11.75 5.75m0 0l-2.5 2.5m0 0a1.75 1.75 0 1 0-1.5 1.5a1.75 1.75 0 1 0 1.5-1.5");
}

</style>
