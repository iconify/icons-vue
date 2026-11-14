<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="loemu8b6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:building-restoration" /></template>
<style>
.loemu8b6a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 6l3.772-2.095a1.5 1.5 0 0 1 1.456 0L16.5 6a1.334 1.334 0 0 1-.648 2.5H8.148A1.334 1.334 0 0 1 7.5 6m-1 2.5v9m5.5-9v9m5.5-9V12M3 17.5h11.3m7.2-.75a2.25 2.25 0 1 1-2.25-2.25m-1.5 3.75L15 21");
}

</style>
