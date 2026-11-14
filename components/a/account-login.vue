<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzcqnyb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:account-login" /></template>
<style>
.dzcqnyb3r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.272 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c1.236 0 2.387.19 3.398.54M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0m8 11h3.75m-2-2l2 2l-2 2m3.25-5.5h2v7h-2");
}

</style>
