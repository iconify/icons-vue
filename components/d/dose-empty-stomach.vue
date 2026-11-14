<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yavunknjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dose-empty-stomach" /></template>
<style>
.yavunknjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 10.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0M3.5 8v12M2.25 3.5v3a1.25 1.25 0 0 0 2.5 0v-3M20.5 12V3.5c-2 1-2.25 5.5 0 7m-4.975 7.25L18 15.275a1.75 1.75 0 0 1 2.475 0a1.75 1.75 0 0 1 0 2.475L18 20.225a1.75 1.75 0 0 1-2.475 0a1.75 1.75 0 0 1 0-2.475m1.238-1.237l2.474 2.474");
}

</style>
