<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9k_j9a5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:jumpsuit" /></template>
<style>
.e9k_j9a5l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 8h8v3l3.5 10.5h-6L12 14l-1.5 7.5h-6L8 11Zm.5-5.5V8m7-5.5V8");
}

</style>
