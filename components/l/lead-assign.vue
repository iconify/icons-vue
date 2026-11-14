<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axrcw4oxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lead-assign" /></template>
<style>
.axrcw4oxw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.034 21H3.5c-.6 0-1-.4-1-1c0-2.75 2.9-4.75 6.5-4.75c3.225 0 5.889 1.605 6.408 3.917M5.25 8.25a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0m11.5 6.5l3.5 3.5l-3.5 3.5");
}

</style>
