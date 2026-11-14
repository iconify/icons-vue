<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z-a8rebpu"/><path class="m7uxsacku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aviary" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m7uxsacku {
  d: path("m8.5 12l2.5 1.5c.5-2.5 3.5-3 4.25-.75c.5 2.75-2.25 4.75-4.75 3.25Z");
}

.z-a8rebpu {
  d: path("M5.5 20.5V11a6.5 6.5 0 0 1 13 0v9.5m-15 0h17M12 4.5v-2");
}

</style>
