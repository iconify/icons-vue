<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emf-8rbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:currency-real" /></template>
<style>
.emf-8rbdc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 19V5h3.75c2 0 3.25 1.25 3.25 3.25S9.25 11.5 7.25 11.5H3.5m4 0l3 7.5m9-10.25c-.4-1.1-1.5-1.65-3-1.75c-1.8.1-2.95 1.05-3 2.5c.05 2.65 5.9 1.45 6 5c-.1 1.4-1.3 2.4-3 2.5c-1.55-.1-2.65-.8-3-1.75m3-10V7m0 10v1.75");
}

</style>
