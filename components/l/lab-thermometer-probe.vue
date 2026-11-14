<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udivu6bzd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:lab-thermometer-probe" /></template>
<style>
.udivu6bzd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.25 15.25l4.5-4.5a3.18 3.18 0 0 1 4.5 4.5l-4.5 4.5a3.18 3.18 0 0 1-4.5-4.5m9-4.5L20.5 3.5M7 17l3.5-3.5");
}

</style>
