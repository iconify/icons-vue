<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqeksrcqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:guest-checkout" /></template>
<style>
.hqeksrcqb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.437 21H3.5c-.6 0-1-.4-1-1c0-2.5 2.5-4.5 5.5-4.5c1.187 0 2.297.313 3.203.847M4.25 8.25a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0m11.938 6.25h3.625A2.19 2.19 0 0 1 22 16.688v2.625a2.19 2.19 0 0 1-2.187 2.187h-3.625A2.19 2.19 0 0 1 14 19.313v-2.625a2.19 2.19 0 0 1 2.188-2.188M14 17.25h8");
}

</style>
