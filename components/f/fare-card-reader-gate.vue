<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvbr0obds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fare-card-reader-gate" /></template>
<style>
.zvbr0obds {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21.5v-13A1.5 1.5 0 0 1 4.5 7h5A1.5 1.5 0 0 1 11 8.5v13M5.75 11h2.5m7.688-6.5h3.375A2.19 2.19 0 0 1 21.5 6.688v1.125A2.19 2.19 0 0 1 19.313 10h-3.375a2.19 2.19 0 0 1-2.188-2.187V6.688A2.19 2.19 0 0 1 15.938 4.5M13.75 6.75h7.75M11 14.5h10.5");
}

</style>
