<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1fv44bcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bulrush" /></template>
<style>
.j1fv44bcb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 2.5v2m0 0zA2.5 2.5 0 0 1 11.5 7v4A2.5 2.5 0 0 1 9 13.5A2.5 2.5 0 0 1 6.5 11V7A2.5 2.5 0 0 1 9 4.5m0 9v8m7.75-13zA2.25 2.25 0 0 1 19 10.75v2.5a2.25 2.25 0 0 1-2.25 2.25a2.25 2.25 0 0 1-2.25-2.25v-2.5a2.25 2.25 0 0 1 2.25-2.25m0 7v6M9 21.5c-2-2.5-4-4-5-5");
}

</style>
