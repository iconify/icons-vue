<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la0-iyb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:alert-queue" /></template>
<style>
.la0-iyb6m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4h17.5M3 9.5h17.5M3 15h7m8.826.504l2.008 3.794a1.5 1.5 0 0 1-1.325 2.202h-4.018a1.5 1.5 0 0 1-1.325-2.202l2.008-3.794a1.5 1.5 0 0 1 2.652 0M17.5 16.75v.75m0 2.25h.01");
}

</style>
