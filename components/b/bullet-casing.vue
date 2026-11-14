<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdc6qpfub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bullet-casing" /></template>
<style>
.bdc6qpfub {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10 9l-2 2.5V19h8v-7.5L14 9Zm0 0V6.5c0-2.25 1-4 2-4s2 1.75 2 4V9M8.25 19h7.5A1.25 1.25 0 0 1 17 20.25a1.25 1.25 0 0 1-1.25 1.25h-7.5A1.25 1.25 0 0 1 7 20.25A1.25 1.25 0 0 1 8.25 19");
}

</style>
