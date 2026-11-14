<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nwy7ti0lm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bobsleigh-team" /></template>
<style>
.nwy7ti0lm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8.5H19a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H4.5a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1Zm1 0a2.25 2.25 0 0 1 4.5 0m2.75 0a2.25 2.25 0 0 1 4.5 0M3.5 18h6m3 0H18q2 0 2.5-1.25");
}

</style>
