<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2e_f1j4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:candelabra" /></template>
<style>
.e2e_f1j4v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 6v3q0 4.5 6 4.5T18 9V6m-6 0v12m-4 3h8l-2-3h-4ZM6 3.25h.01m5.99 0h.01m5.99 0h.01");
}

</style>
