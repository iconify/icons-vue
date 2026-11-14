<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctkfbpb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:filament-spool" /></template>
<style>
.ctkfbpb1i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 5.5a8.5 2.5 0 1 0 17 0a8.5 2.5 0 1 0-17 0m0 13a8.5 2.5 0 1 0 17 0a8.5 2.5 0 1 0-17 0M8 7.75v8.5m8-8.5v8.5m0-4.75c3.5 0 5.5 1 5.5 3");
}

</style>
