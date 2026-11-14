<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gimh27bxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:list-roman" /></template>
<style>
.gimh27bxb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.5 6.5h9m-9 8.5h9M3.5 4H7M5.25 4v5M3.5 9H7m-4.5 3.5h6m-4.5 0v5m3-5v5m-4.5 0h6");
}

</style>
