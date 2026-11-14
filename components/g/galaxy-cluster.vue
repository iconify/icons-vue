<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kso7flbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:galaxy-cluster" /></template>
<style>
.kso7flbeg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6.5a4.5 2.75 0 1 0 9 0a4.5 2.75 0 1 0-9 0m9 4.5a4.5 2.75 0 1 0 9 0a4.5 2.75 0 1 0-9 0m-8.5 6.5a4.5 2.75 0 1 0 9 0a4.5 2.75 0 1 0-9 0m4-11h.01M16.5 11h.01M8 17.5h.01");
}

</style>
