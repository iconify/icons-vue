<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6b-_9bad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lab-robot" /></template>
<style>
.z6b-_9bad {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20h7m-3.5 0L8.75 8.5M7 6.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m4 0h5.5V10m-2 2.75V10h4v2.75m-3.75 2.75h4a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 18.75 20h-4A1.75 1.75 0 0 1 13 18.25v-1a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
