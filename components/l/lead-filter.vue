<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwvyn6rkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lead-filter" /></template>
<style>
.dwvyn6rkt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.372 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c1.002 0 1.948.125 2.809.359M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0m10.226 8h2.298a1.036 1.036 0 0 1 .851 1.625l-.858 1.24a1.5 1.5 0 0 0-.267.854v1.273a.585.585 0 0 1-.875.508l-.119-.068A1.5 1.5 0 0 1 17 19.13v-.411a1.5 1.5 0 0 0-.267-.854l-.858-1.24A1.036 1.036 0 0 1 16.726 15");
}

</style>
