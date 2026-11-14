<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eko6wybyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dental-crown" /></template>
<style>
.eko6wybyq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 11c0-5 1-8 4.5-8c2 0 2.5 1.5 4 1.5S14 3 16 3c3.5 0 4.5 3 4.5 8ZM6 11l1 8.5c.25 1.5 2 1.5 2.25 0l1-4.5c.25-1 3.25-1 3.5 0l1 4.5c.25 1.5 2 1.5 2.25 0l1-8.5");
}

</style>
