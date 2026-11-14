<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c77vqfbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:film-director" /></template>
<style>
.c77vqfbrm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.75V13M18 2.75V13M7.5 3.5h9A1.5 1.5 0 0 1 18 5v.5A1.5 1.5 0 0 1 16.5 7h-9A1.5 1.5 0 0 1 6 5.5V5a1.5 1.5 0 0 1 1.5-1.5m-3 6.5h15M6 13h12M6 13l12 8.5m0-8.5L6 21.5");
}

</style>
