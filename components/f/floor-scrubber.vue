<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lr8yz-jvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:floor-scrubber" /></template>
<style>
.lr8yz-jvj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15.5v-5a2 2 0 0 1 2-2H13a2 2 0 0 1 2 2v5Zm11.5-7l4.5-6m-1.5 0l4 1.75M3 17.5a5.75 1.75 0 1 0 11.5 0a5.75 1.75 0 1 0-11.5 0m2 1.75L4.5 21m4.25-1.75V21m3.75-1.75L13 21m3-3.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m1 4h.01m3.49 0h.01");
}

</style>
