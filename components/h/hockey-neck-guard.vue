<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ho6n06iac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hockey-neck-guard" /></template>
<style>
.ho6n06iac {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 6c2.5 3.5 9.5 3.5 12 0v6c0 5-3 8.5-6 8.5S6 17 6 12Zm0 0L3 3.5M18 6l3-2.5");
}

</style>
