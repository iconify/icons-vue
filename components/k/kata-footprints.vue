<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9lrnbb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kata-footprints" /></template>
<style>
.d9lrnbb9t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.25 18a3.25 2.5 0 1 0 6.5 0a3.25 2.5 0 1 0-6.5 0m6.5-6a3.25 2.5 0 1 0 6.5 0a3.25 2.5 0 1 0-6.5 0m6.5-6a3.25 2.5 0 1 0 6.5 0a3.25 2.5 0 1 0-6.5 0");
}

</style>
