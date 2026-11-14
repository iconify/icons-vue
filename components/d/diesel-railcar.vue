<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f365p7wfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:diesel-railcar" /></template>
<style>
.f365p7wfk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 6.5h7v9H2.5V8A1.5 1.5 0 0 1 4 6.5m9 0h7A1.5 1.5 0 0 1 21.5 8v7.5H13Zm-7.5 0v-3H8v3m3 6h2m-8 5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m10.5 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M5.25 10.25h3m7.5 0h3");
}

</style>
