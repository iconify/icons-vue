<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb95sccol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:integral" /></template>
<style>
.rb95sccol {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 4.5c-.75-.75-1.75-1-2.5-.75c-1.1.35-1.6 1.25-1.75 2.5l-1.5 11.5c-.15 1.25-.65 2.15-1.75 2.5c-.75.25-1.75 0-2.5-.75");
}

</style>
