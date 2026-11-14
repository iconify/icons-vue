<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m65chdjxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:layers-merge" /></template>
<style>
.m65chdjxx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.817 10.931l5.251 2.771a1.75 1.75 0 0 1 0 3.096l-5.251 2.771a1.75 1.75 0 0 1-1.634 0l-5.251-2.771a1.75 1.75 0 0 1 0-3.096l5.251-2.771a1.75 1.75 0 0 1 1.634 0M4.5 2.5L12 7m7.5-4.5L12 7");
}

</style>
