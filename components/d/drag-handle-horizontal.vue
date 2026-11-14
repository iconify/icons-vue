<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twjzex7uu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drag-handle-horizontal" /></template>
<style>
.twjzex7uu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 9a1 1 0 1 0 2 0a1 1 0 1 0-2 0M11 9a1 1 0 1 0 2 0a1 1 0 1 0-2 0m6.5 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0m-13 6a1 1 0 1 0 2 0a1 1 0 1 0-2 0m6.5 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0m6.5 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>
