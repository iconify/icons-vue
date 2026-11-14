<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1m995bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:breaking-board-plastic" /></template>
<style>
.h1m995bfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 7.5h5.888a1.75 1.75 0 0 1 1.674 2.26l-2.434 8A1.75 1.75 0 0 1 7.703 19H4.25a1.75 1.75 0 0 1-1.75-1.75v-8A1.75 1.75 0 0 1 4.25 7.5M17.797 5h1.953a1.75 1.75 0 0 1 1.75 1.75v8a1.75 1.75 0 0 1-1.75 1.75h-4.388a1.75 1.75 0 0 1-1.674-2.26l2.434-8A1.75 1.75 0 0 1 17.797 5");
}

</style>
