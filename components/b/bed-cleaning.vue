<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sehtgdbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bed-cleaning" /></template>
<style>
.sehtgdbto {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4.5V20m0-7.5h16a2 2 0 0 1 2 2V20M3 16.5h18M16.119 3.631l.408.746a1.5 1.5 0 0 0 .596.596l.746.408a.705.705 0 0 1 0 1.238l-.746.408a1.5 1.5 0 0 0-.596.596l-.408.746a.705.705 0 0 1-1.238 0l-.408-.746a1.5 1.5 0 0 0-.596-.596l-.746-.408a.705.705 0 0 1 0-1.238l.746-.408a1.5 1.5 0 0 0 .596-.596l.408-.746a.705.705 0 0 1 1.238 0");
}

</style>
