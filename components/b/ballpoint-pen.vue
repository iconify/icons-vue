<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v25vjubpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ballpoint-pen" /></template>
<style>
.v25vjubpw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.364 5.636za2.5 2.5 0 0 1 0 3.536L12 15.536a2.5 2.5 0 0 1-3.536 0a2.5 2.5 0 0 1 0-3.536l6.364-6.364a2.5 2.5 0 0 1 3.536 0M5.5 18.5L4 20");
}

</style>
