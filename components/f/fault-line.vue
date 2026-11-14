<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-kwl_ett"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fault-line" /></template>
<style>
.x-kwl_ett {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 7.25H11l-1.5 4.5l3 3l-2 4.5h-6a2 2 0 0 1-2-2v-8a2 2 0 0 1 2-2M15 4.75h4.5a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2h-5l2-4.5l-3-3Z");
}

</style>
