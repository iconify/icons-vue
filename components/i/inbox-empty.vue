<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwddwvh2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:inbox-empty" /></template>
<style>
.qwddwvh2l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12H8l1.5 3h5l1.5-3h5.5v6.5A2.5 2.5 0 0 1 19 21H5a2.5 2.5 0 0 1-2.5-2.5ZM9 5.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0m.75 3.5l4.5-7");
}

</style>
