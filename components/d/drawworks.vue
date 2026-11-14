<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4e_0vb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drawworks" /></template>
<style>
.p4e_0vb5j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 13.5a1.75 6.5 0 1 0 3.5 0a1.75 6.5 0 1 0-3.5 0m11 0a1.75 6.5 0 1 0 3.5 0a1.75 6.5 0 1 0-3.5 0M6.5 10h8m-8 7h8m-4-14.5V10m7.25 3.5h2.75v4");
}

</style>
