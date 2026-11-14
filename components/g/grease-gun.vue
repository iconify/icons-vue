<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7c5anbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:grease-gun" /></template>
<style>
.d7c5anbak {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 8.5h7.5A1.75 1.75 0 0 1 17 10.25v3.5a1.75 1.75 0 0 1-1.75 1.75h-7.5A1.75 1.75 0 0 1 6 13.75v-3.5A1.75 1.75 0 0 1 7.75 8.5M4.5 10zA1.5 1.5 0 0 1 6 11.5v1A1.5 1.5 0 0 1 4.5 14A1.5 1.5 0 0 1 3 12.5v-1A1.5 1.5 0 0 1 4.5 10M9 8.5v-3h5m3 6.5h1.5a2.5 2.5 0 0 1 2.5 2.5V19");
}

</style>
