<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujkzyabeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:decentralized-network" /></template>
<style>
.ujkzyabeq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m8 6a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-3 10a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-3-10a2 2 0 1 0 4 0a2 2 0 1 0-4 0m12.5-4.25l3 2.5m1.75 4.75l-1.5 4m-3.75 3h-4m-5.25-7l1.5 4m.25-8.75l3-2.5");
}

</style>
