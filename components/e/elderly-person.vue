<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccnsfobtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:elderly-person" /></template>
<style>
.ccnsfobtt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2 3.5L9 14m0 0l2.5 3v4M9 14l-2.5 7m0-10.5l3.25-2l4.75 3m0 0V21");
}

</style>
