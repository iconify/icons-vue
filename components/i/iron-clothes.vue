<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1za0fb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:iron-clothes" /></template>
<style>
.w1za0fb8t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.25h18.5v-3.5a3.5 3.5 0 0 0-3.5-3.5h-8.5c-3.25 0-5.5 3-6.5 7m6.75-7l1-3.25H18a1 1 0 0 1 1 1v2.25M9 3c-.9 1.15.9 2.1 0 3.25M13 3c-.9 1.15.9 2.1 0 3.25M17 3c-.9 1.15.9 2.1 0 3.25");
}

</style>
