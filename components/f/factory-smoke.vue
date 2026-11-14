<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tis5x9brb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:factory-smoke" /></template>
<style>
.tis5x9brb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20.5V12l4.5-3v3L12 9v3h3.5V7.5h4v13ZM14.25 4.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m4.25-.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M6 16h2m2.5 0h2");
}

</style>
