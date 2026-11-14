<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5j3xumqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:impact-trees-planted" /></template>
<style>
.c5j3xumqq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 8.5a6 6 0 1 0 12 0a6 6 0 1 0-12 0m6 6V21m8.5 0v-4m0 0c0-2 1.5-3 3.5-3c0 2-1.5 3-3.5 3m0 1c0-1.5-1.25-2.5-3-2.5c0 1.5 1.25 2.5 3 2.5");
}

</style>
