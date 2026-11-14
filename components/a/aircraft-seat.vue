<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u64ucf1ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aircraft-seat" /></template>
<style>
.u64ucf1ro {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.5 2.5h3A1.5 1.5 0 0 1 20 4v13.5a1.5 1.5 0 0 1-1.5 1.5h-13A1.5 1.5 0 0 1 4 17.5v-2A1.5 1.5 0 0 1 5.5 14H14V4a1.5 1.5 0 0 1 1.5-1.5m-8 8H14M7 19v2.5M17 19v2.5");
}

</style>
