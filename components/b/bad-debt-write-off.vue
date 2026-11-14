<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjq5yfa_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bad-debt-write-off" /></template>
<style>
.yjq5yfa_g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.82 20.76l-.32.24l-2-1.5l-2 1.5l-2-1.5l-2 1.5V2.5h12v8.7M6.5 7h6m-6 4h6m1.25 6.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0M15 15l5 5");
}

</style>
