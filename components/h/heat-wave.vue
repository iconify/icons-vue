<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjpydggyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:heat-wave" /></template>
<style>
.fjpydggyc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 14.6V5a2 2 0 0 1 4 0v9.6a3.25 3.25 0 1 1-4 0M13.75 4q-1.5 2 0 4t0 4t0 4t0 4m4.5-16q-1.5 2 0 4t0 4t0 4t0 4");
}

</style>
