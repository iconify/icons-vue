<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fk8g8kbuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:beat-maker-play" /></template>
<style>
.fk8g8kbuz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 3.5h15.5a1.75 1.75 0 0 1 1.75 1.75v1.5a1.75 1.75 0 0 1-1.75 1.75H4.25A1.75 1.75 0 0 1 2.5 6.75v-1.5A1.75 1.75 0 0 1 4.25 3.5m6.319 9.36l3.01 1.593a1.75 1.75 0 0 1 0 3.094l-3.01 1.593A1.75 1.75 0 0 1 8 17.593v-3.186a1.75 1.75 0 0 1 2.569-1.547M7.25 3.5v5m4.75-5v5m4.75-5v5");
}

</style>
