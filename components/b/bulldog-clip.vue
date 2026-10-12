<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pep9rpb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bulldog-clip" /></template>
<style>
.pep9rpb-b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 11.5V8.25A1.25 1.25 0 0 1 8.25 7h1a1.25 1.25 0 0 1 1.25 1.25v3.25m3 0V8.25A1.25 1.25 0 0 1 14.75 7h1A1.25 1.25 0 0 1 17 8.25v3.25m-8.5 0h7q1.5 0 1.89 1.45l.97 3.6Q18.75 18 17.25 18H6.75q-1.5 0-1.11-1.45l.97-3.6Q7 11.5 8.5 11.5M8 18v3.25h8V18");
}

</style>
