<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9wngnbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:inflammation" /></template>
<style>
.h9wngnbjv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19.5H6C6 15 8.75 13 12 13s6 2 6 6.5h3.5M5.75 13.25L4.5 12m13.75 1.25L19.5 12M9 9.5c-1-1 1-3 0-4c-.75-.75 0-2 .25-2.5M15 9.5c-1-1 1-3 0-4c-.75-.75 0-2 .25-2.5");
}

</style>
