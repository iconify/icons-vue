<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvr6fh7rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:exponent" /></template>
<style>
.fvr6fh7rs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 10.5l8 9m0-9l-8 9M15 6c0-1.1.9-2 2-2s2 .9 2 2c0 1.75-4 2.5-4 4.75h4.5");
}

</style>
