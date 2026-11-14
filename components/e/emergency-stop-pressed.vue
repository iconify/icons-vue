<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ud5raeb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:emergency-stop-pressed" /></template>
<style>
.ud5raeb9h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13h19v6a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2ZM6 13c0-5.5 12-5.5 12 0M9.5 3L12 5.5L14.5 3");
}

</style>
