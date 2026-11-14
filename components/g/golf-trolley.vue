<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blul75b-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:golf-trolley" /></template>
<style>
.blul75b-o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.125 7h1.75A2.625 2.625 0 0 1 11.5 9.625v7.75A2.625 2.625 0 0 1 8.875 20h-1.75A2.625 2.625 0 0 1 4.5 17.375v-7.75A2.625 2.625 0 0 1 7.125 7M11.5 9.5l5-5.5m-5 14h4m0 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0M7 7V3.5H5M9.5 7V2.5h2");
}

</style>
