<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ms-6hwtbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:concealer" /></template>
<style>
.ms-6hwtbe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.875 10h2.25a2.625 2.625 0 0 1 2.625 2.625v5.25A2.625 2.625 0 0 1 8.125 20.5h-2.25a2.625 2.625 0 0 1-2.625-2.625v-5.25A2.625 2.625 0 0 1 5.875 10M5.5 10V5a1.5 1.5 0 0 1 3 0v5m5 10.5V11a3.5 3.5 0 0 1 7 0v9.5Z");
}

</style>
