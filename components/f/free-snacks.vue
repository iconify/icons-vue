<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pw0rmlbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:free-snacks" /></template>
<style>
.pw0rmlbur {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M20.5 9.75a8.75 8.75 0 1 1-6.25-6.25a2.5 2.5 0 0 0 3.25 3a2.5 2.5 0 0 0 3 3.25M8.5 9h.01m3.99 3.5h.01m-4.01 3h.01M15 16h.01");
}

</style>
