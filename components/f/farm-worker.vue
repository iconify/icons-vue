<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx0xhkbxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:farm-worker" /></template>
<style>
.sx0xhkbxo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 8h19M8 8c0-4 1.5-5 4-5s4 1 4 5M8 8v2.5a4 4 0 0 0 8 0V8M4.5 21.5c0-2.5 3.25-4.25 7.5-4.25s7.5 1.75 7.5 4.25");
}

</style>
