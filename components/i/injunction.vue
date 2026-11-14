<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3arpyzie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:injunction" /></template>
<style>
.b3arpyzie {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.975 3.25h6.05a1.75 1.75 0 0 1 1.238.513l3.974 3.974a1.75 1.75 0 0 1 .513 1.238v6.05a1.75 1.75 0 0 1-.513 1.238l-3.974 3.974a1.75 1.75 0 0 1-1.238.513h-6.05a1.75 1.75 0 0 1-1.238-.513l-3.974-3.974a1.75 1.75 0 0 1-.513-1.238v-6.05a1.75 1.75 0 0 1 .513-1.238l3.974-3.974a1.75 1.75 0 0 1 1.238-.513M7.5 12h9");
}

</style>
