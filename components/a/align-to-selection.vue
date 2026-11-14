<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1q5i-w8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:align-to-selection" /></template>
<style>
.z1q5i-w8z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6V3h3m4 0h4m4 0h3v3m0 4v4m0 4v3h-3m-4 0h-4m-4 0H3v-3m0-4v-4m5.25-3h7.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75h-7.5A1.75 1.75 0 0 1 6.5 8.75A1.75 1.75 0 0 1 8.25 7m0 6.5h3.5a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 11.75 17h-3.5a1.75 1.75 0 0 1-1.75-1.75a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
