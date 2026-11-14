<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvutvgcgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:green-building" /></template>
<style>
.kvutvgcgm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 2.5h5a2.625 2.625 0 0 1 2.625 2.625v13.75a2.625 2.625 0 0 1-2.625 2.625h-5A2.625 2.625 0 0 1 3 18.875V5.125A2.625 2.625 0 0 1 5.625 2.5M6.5 7h.01m3.24 0h.01M6.5 11h.01m3.24 0h.01M6.5 15h.01m3.24 0h.01M16 21.5c0-4.5 2-6.5 5.75-6.5c0 4.5-2 6.5-5.75 6.5");
}

</style>
