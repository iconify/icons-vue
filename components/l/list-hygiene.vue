<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7khk349y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:list-hygiene" /></template>
<style>
.n7khk349y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4h18M3 9.5h18M3 15h8.5m6.25-1q.5 3.25 3.75 3.75q-3.25.5-3.75 3.75q-.5-3.25-3.75-3.75q3.25-.5 3.75-3.75");
}

</style>
