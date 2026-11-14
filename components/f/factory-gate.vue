<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5ifepbot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:factory-gate" /></template>
<style>
.c5ifepbot {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 11h.5a1.75 1.75 0 0 1 1.75 1.75v6a1.75 1.75 0 0 1-1.75 1.75h-.5a1.75 1.75 0 0 1-1.75-1.75v-6A1.75 1.75 0 0 1 5.25 11m2.799-1.049l8.66-5a1.5 1.5 0 0 1 2.049.549a1.5 1.5 0 0 1-.549 2.049l-8.66 5A1.5 1.5 0 0 1 7.5 12a1.5 1.5 0 0 1 .549-2.049m2.382-1.375l1.5 2.598m2.18-4.723l1.5 2.598");
}

</style>
