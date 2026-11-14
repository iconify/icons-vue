<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c816smbot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bin-bag-tied" /></template>
<style>
.c816smbot {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 8c-4.5 1.5-6 5-6 9v2A2.5 2.5 0 0 0 7 21.5h10a2.5 2.5 0 0 0 2.5-2.5v-2c0-4-1.5-7.5-6-9ZM12 8c-3-.5-5.5-2.5-4.5-4.25C8.5 2.25 11 4 12 8c1-4 3.5-5.75 4.5-4.25C17.5 5.5 15 7.5 12 8");
}

</style>
