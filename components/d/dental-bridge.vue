<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wnc3sib1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dental-bridge" /></template>
<style>
.wnc3sib1b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7c0-1.5 1-2 2-2h15c1 0 2 .5 2 2v4c0 1-.5 1.5-1 2l-1 5.5c-.25 1-1.5 1-1.75 0L16.5 13c-1.5 3-7.5 3-9 0l-1.25 5.5c-.25 1-1.5 1-1.75 0l-1-5.5c-.5-.5-1-1-1-2ZM9 5v5m6-5v5");
}

</style>
