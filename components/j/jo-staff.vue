<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itbpxvb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:jo-staff" /></template>
<style>
.itbpxvb6l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.303 6.697L6.697 17.303M19.601 4.045l.354.354a1.75 1.75 0 0 1 0 2.474a1.75 1.75 0 0 1-2.475 0l-.353-.353a1.75 1.75 0 0 1 0-2.475a1.75 1.75 0 0 1 2.474 0M6.52 17.127l.353.353a1.75 1.75 0 0 1 0 2.475a1.75 1.75 0 0 1-2.474 0l-.354-.354a1.75 1.75 0 0 1 0-2.474a1.75 1.75 0 0 1 2.475 0");
}

</style>
