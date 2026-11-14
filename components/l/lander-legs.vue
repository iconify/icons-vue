<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kw33jdbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lander-legs" /></template>
<style>
.kw33jdbvp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.654 4.75h6.692a1.75 1.75 0 0 1 1.609 1.061l1.5 3.5a1.75 1.75 0 0 1-1.609 2.439H7.154a1.75 1.75 0 0 1-1.609-2.439l1.5-3.5A1.75 1.75 0 0 1 8.654 4.75m-1.154 7l-3 7.5m-2 0h4m10-7.5l3 7.5m-2 0h4m-9.5-7.5v7.5m-2 0h4");
}

</style>
