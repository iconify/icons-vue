<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwi_brmie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:help-contact" /></template>
<style>
.dwi_brmie {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 11.75v-1.5a7.25 7.25 0 0 1 14.5 0v1.5m-14.5 0zA2.25 2.25 0 0 1 7 14v2a2.25 2.25 0 0 1-2.25 2.25A2.25 2.25 0 0 1 2.5 16v-2a2.25 2.25 0 0 1 2.25-2.25m14.5 0zA2.25 2.25 0 0 1 21.5 14v2a2.25 2.25 0 0 1-2.25 2.25A2.25 2.25 0 0 1 17 16v-2a2.25 2.25 0 0 1 2.25-2.25m0 6.5c0 2.25-1.75 2.75-6.75 2.75");
}

</style>
