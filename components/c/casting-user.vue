<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgfpqebnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:casting-user" /></template>
<style>
.mgfpqebnn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 7.25a4 4 0 1 0 8 0a4 4 0 1 0-8 0M3 21c0-4 3.25-6.75 7.5-6.75c1.209 0 2.338.223 3.333.633M16.5 18.25A2.75 2.75 0 0 1 19.25 21m-2.75-5.25A5.25 5.25 0 0 1 21.75 21m-5.25 0h.01");
}

</style>
