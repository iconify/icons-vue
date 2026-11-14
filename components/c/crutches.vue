<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t__qncbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crutches" /></template>
<style>
.t__qncbgc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 3v8l2 3l2-3V3m-5 0h6m-5 5h4m-2 6v7m7-18v8l2 3l2-3V3m-5 0h6m-5 5h4m-2 6v7");
}

</style>
