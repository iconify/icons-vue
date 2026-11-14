<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="omc6c8b5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:football-trophy-american" /></template>
<style>
.omc6c8b5m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8a10 10 0 0 1 17 0a10 10 0 0 1-17 0m8.5 4.75V16m-3.5 0h7l1.5 5H7ZM9 8h6m-4.5-1.25v2.5m3-2.5v2.5");
}

</style>
