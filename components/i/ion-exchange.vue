<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3ugthbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ion-exchange" /></template>
<style>
.u3ugthbuk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0m10 10a4 4 0 1 0 8 0a4 4 0 1 0-8 0M7 5.5v3M5.5 7h3m7 10h3M13.75 5.5q5.75 0 5.75 4.75M17.25 8l2.25 2.25L21.75 8m-11.5 10.5q-5.75 0-5.75-4.75M2.25 16l2.25-2.25L6.75 16");
}

</style>
