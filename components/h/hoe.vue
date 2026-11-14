<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_i5robma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hoe" /></template>
<style>
.m_i5robma {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 13L20 3M5.37 17.5h3.26a1.5 1.5 0 0 0 1.464-1.825l-.333-1.5A1.5 1.5 0 0 0 8.297 13H5.703a1.5 1.5 0 0 0-1.464 1.175l-.333 1.5A1.5 1.5 0 0 0 5.37 17.5m-2.87 3h19");
}

</style>
