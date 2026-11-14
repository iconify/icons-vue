<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0jkzw15g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:contract-archive" /></template>
<style>
.q0jkzw15g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 12V2.5H14l2.75 2.75V12M3 12h18M4.5 12v7.5a2 2 0 0 0 2 2h11a2 2 0 0 0 2-2V12m-9.25-6h3m-3 3h3.5M10 16.5h4");
}

</style>
