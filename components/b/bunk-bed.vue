<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbljg9bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bunk-bed" /></template>
<style>
.jbljg9bnk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3v18m17-18v18m-17-11h17m-17 8h17M7.75 6.5h1a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 8.75 10h-1A1.75 1.75 0 0 1 6 8.25A1.75 1.75 0 0 1 7.75 6.5m0 8h1a1.75 1.75 0 0 1 1.75 1.75A1.75 1.75 0 0 1 8.75 18h-1A1.75 1.75 0 0 1 6 16.25a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
