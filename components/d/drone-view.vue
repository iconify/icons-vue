<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0t3-3bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drone-view" /></template>
<style>
.d0t3-3bpw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.625 9h.75A2.625 2.625 0 0 1 15 11.625v.75A2.625 2.625 0 0 1 12.375 15h-.75A2.625 2.625 0 0 1 9 12.375v-.75A2.625 2.625 0 0 1 11.625 9M4 4l5 5m11-5l-5 5M4 20l5-5m11 5l-5-5M2.5 4a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m16 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-16 16a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m16 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
