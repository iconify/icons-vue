<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="enonzbp8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:car-bulb" /></template>
<style>
.enonzbp8f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 12V8.5a4 4 0 0 1 8 0V12H15v3H4v-3ZM7 15v5.5m5-5.5v5.5M17 5l3.5-1.5m-3 5.5h4M18 12.5l3 1.5");
}

</style>
