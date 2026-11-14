<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4dm0ij_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:colonnade" /></template>
<style>
.m4dm0ij_b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 3h15.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75H4.25A1.75 1.75 0 0 1 2.5 4.75A1.75 1.75 0 0 1 4.25 3m1 3.5zA1.25 1.25 0 0 1 6.5 7.75v12A1.25 1.25 0 0 1 5.25 21A1.25 1.25 0 0 1 4 19.75v-12A1.25 1.25 0 0 1 5.25 6.5m6.75 0za1.25 1.25 0 0 1 1.25 1.25v12A1.25 1.25 0 0 1 12 21a1.25 1.25 0 0 1-1.25-1.25v-12A1.25 1.25 0 0 1 12 6.5m6.75 0zA1.25 1.25 0 0 1 20 7.75v12A1.25 1.25 0 0 1 18.75 21a1.25 1.25 0 0 1-1.25-1.25v-12a1.25 1.25 0 0 1 1.25-1.25");
}

</style>
