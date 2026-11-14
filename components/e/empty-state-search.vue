<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvx-sqbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:empty-state-search" /></template>
<style>
.fvx-sqbqe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7V4.5a2 2 0 0 1 2-2H7m3 0h4m3 0h2.5a2 2 0 0 1 2 2V7m0 3v4m0 3v2.5a2 2 0 0 1-2 2H17m-3 0h-4m-3 0H4.5a2 2 0 0 1-2-2V17m0-3v-4M7 11a4 4 0 1 0 8 0a4 4 0 1 0-8 0m7 3l2.5 2.5");
}

</style>
