<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5ugggbpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:heart-key" /></template>
<style>
.d5ugggbpq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.5 12l-5-6.25A4 4 0 0 0 3.75 12a4 4 0 0 0 4.75 6.25Zm0 0h7.75m-3 0v3.5m3-3.5v3");
}

</style>
