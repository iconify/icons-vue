<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0-m7-b4z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:laminar-flow" /></template>
<style>
.h0-m7-b4z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9C9 9 13 5 21.5 5m-19 9c6.5 0 10.5-4 19-4m-19 9c6.5 0 10.5-4 19-4");
}

</style>
