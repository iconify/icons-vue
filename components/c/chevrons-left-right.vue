<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afpa97-1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chevrons-left-right" /></template>
<style>
.afpa97-1d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 8.5L2.5 12L6 15.5m4-7L6.5 12l3.5 3.5m8-7l3.5 3.5l-3.5 3.5m-4-7l3.5 3.5l-3.5 3.5");
}

</style>
