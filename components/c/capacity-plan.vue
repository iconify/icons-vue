<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5ho2ob2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:capacity-plan" /></template>
<style>
.t5ho2ob2e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.375 4.5h9.25A4.375 4.375 0 0 1 21 8.875v7.75A4.375 4.375 0 0 1 16.625 21h-9.25A4.375 4.375 0 0 1 3 16.625v-7.75A4.375 4.375 0 0 1 7.375 4.5M3 9.5h18m-13-7V6m8-3.5V6M8 18v-2m4 2v-3.5m4 3.5v-5.5");
}

</style>
