<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myk9gzuqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:letterpress" /></template>
<style>
.myk9gzuqa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3h14M8.5 13.5L12 6l3.5 7.5m-7.875 0h8.75A2.625 2.625 0 0 1 19 16.125v2.25A2.625 2.625 0 0 1 16.375 21h-8.75A2.625 2.625 0 0 1 5 18.375v-2.25A2.625 2.625 0 0 1 7.625 13.5m2.625-3h3.5");
}

</style>
