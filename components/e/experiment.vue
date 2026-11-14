<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6o3ktggl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:experiment" /></template>
<style>
.g6o3ktggl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 3v6l-4.75 9.25c-.5 1.25.25 2.5 1.5 2.5h11.5c1.25 0 2-1.25 1.5-2.5L14.5 9V3M8 3h8M7 15h10m-6.5 3h.01m2.99 0h.01");
}

</style>
