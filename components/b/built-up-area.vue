<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mz3_inrqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:built-up-area" /></template>
<style>
.mz3_inrqf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 3h6A1.5 1.5 0 0 1 12 4.5v6a1.5 1.5 0 0 0 1.5 1.5h6a1.5 1.5 0 0 1 1.5 1.5v6a1.5 1.5 0 0 1-1.5 1.5h-15A1.5 1.5 0 0 1 3 19.5v-15A1.5 1.5 0 0 1 4.5 3M3 6.5L6.5 3M3 11l8-8M3 15.5l9-9M3 20l9-9M6.5 21l9-9M11 21l9-9m-4.5 9l5.5-5.5");
}

</style>
