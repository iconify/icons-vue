<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjwndbcrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dog-walk-route" /></template>
<style>
.sjwndbcrf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 19a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m6.25 0h2.25m2.5 0Q17 19 17 16.25m0-2.5V11.5m0 0C15.5 10 14 8.25 14 6a3 3 0 0 1 6 0c0 2.25-1.5 4-3 5.5M17 6h.01");
}

</style>
