<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t34d7mz3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hostel" /></template>
<style>
.t34d7mz3t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 2.5v19m18-19v19M3 9.5h18M3 17h18M7.125 6.25h.75A1.625 1.625 0 0 1 9.5 7.875A1.625 1.625 0 0 1 7.875 9.5h-.75A1.625 1.625 0 0 1 5.5 7.875A1.625 1.625 0 0 1 7.125 6.25m0 7.5h.75A1.625 1.625 0 0 1 9.5 15.375A1.625 1.625 0 0 1 7.875 17h-.75A1.625 1.625 0 0 1 5.5 15.375a1.625 1.625 0 0 1 1.625-1.625M17 9.5v12m0-8.25h4M17 20h4");
}

</style>
