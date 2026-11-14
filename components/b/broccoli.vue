<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3x0f42ij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:broccoli" /></template>
<style>
.g3x0f42ij {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 20.5h6L14 14h-4ZM6 13c-2.5 0-3-3.5-.5-4.5c0-3 3.5-4 5-2C12 4 16 5 16 7.5c3-.5 4.5 3 2 4.5c-.5 2-4 2-6 1.5c-2 .5-5 .5-6-.5");
}

</style>
