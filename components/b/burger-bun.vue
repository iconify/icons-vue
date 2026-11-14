<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvox3idfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:burger-bun" /></template>
<style>
.hvox3idfs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10.25c.5-8.5 17.5-8.5 18 0Zm0 3.5q1.5-1.5 3 0t3 0t3 0t3 0t3 0t3 0m-16.25 3.5h14.5A1.75 1.75 0 0 1 21 19a1.75 1.75 0 0 1-1.75 1.75H4.75A1.75 1.75 0 0 1 3 19a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
