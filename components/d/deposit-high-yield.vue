<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wzi5eab3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deposit-high-yield" /></template>
<style>
.wzi5eab3a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 18.5l9.5-13m-10.25 2a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m6.5 9a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M18.5 21V4m-3 3l3-3l3 3");
}

</style>
