<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ipw5ddmch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-validation" /></template>
<style>
.ipw5ddmch {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 7.5L5 9l2.5-3M11 7.5h9.5m-17 5L5 14l2.5-3m3.5 1.5h9.5M3.5 17L5 18.5l2.5-3M11 17h6");
}

</style>
