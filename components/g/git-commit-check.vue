<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sy6dfvbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:git-commit-check" /></template>
<style>
.sy6dfvbzp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10h4.75m0 0a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0m8.5 0h5.75m-6.75 8l2 2L21 15.75");
}

</style>
