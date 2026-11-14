<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fr54h8c2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gantt-search" /></template>
<style>
.fr54h8c2u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5v19M7.5 3h6A1.5 1.5 0 0 1 15 4.5A1.5 1.5 0 0 1 13.5 6h-6A1.5 1.5 0 0 1 6 4.5A1.5 1.5 0 0 1 7.5 3m4 6h7a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-7a1.5 1.5 0 0 1-1.5-1.5A1.5 1.5 0 0 1 11.5 9m-3 6H11a1.5 1.5 0 0 1 1.5 1.5A1.5 1.5 0 0 1 11 18H8.5A1.5 1.5 0 0 1 7 16.5A1.5 1.5 0 0 1 8.5 15m6.75 2.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m4 1.75L21 21");
}

</style>
