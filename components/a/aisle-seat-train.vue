<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n88nt-bjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aisle-seat-train" /></template>
<style>
.n88nt-bjl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.375 2.5h5.25A1.875 1.875 0 0 1 16.5 4.375a1.875 1.875 0 0 1-1.875 1.875h-5.25A1.875 1.875 0 0 1 7.5 4.375A1.875 1.875 0 0 1 9.375 2.5M6.5 15v-4a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2v4M6.25 15h11.5a1.75 1.75 0 0 1 1.75 1.75a1.75 1.75 0 0 1-1.75 1.75H6.25a1.75 1.75 0 0 1-1.75-1.75A1.75 1.75 0 0 1 6.25 15M7 18.5v3m10-3v3");
}

</style>
