<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqrdqh2ny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dental-scaler" /></template>
<style>
.bqrdqh2ny {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 16.5L8 13a2.12 2.12 0 0 1 3 0a2.12 2.12 0 0 1 0 3l-3.5 3.5a2.12 2.12 0 0 1-3 0a2.12 2.12 0 0 1 0-3M11 13l3.5-3.5m0 0c0-4 2.5-6.5 5.25-6.5c1.75 0 1.75 2.5-.25 4.25");
}

</style>
