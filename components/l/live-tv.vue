<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssz2i71et"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:live-tv" /></template>
<style>
.ssz2i71et {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 10h12a3.5 3.5 0 0 1 3.5 3.5v4A3.5 3.5 0 0 1 18 21H6a3.5 3.5 0 0 1-3.5-3.5v-4A3.5 3.5 0 0 1 6 10m4.25-3.031a3.5 3.5 0 0 1 3.5 0M8.5 3.938a7 7 0 0 1 7 0");
}

</style>
