<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mbbp5jbyf"/><path class="m6i9yrbgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chat-rating" /></template>
<style>
.m6i9yrbgp {
  d: path("m12 5.75l1 2.5l2.75.25l-2 1.75l.5 2.75L12 11.5L9.75 13l.5-2.75l-2-1.75L11 8.25Z");
}

.mbbp5jbyf {
  d: path("M5 3h14a2.5 2.5 0 0 1 2.5 2.5V14a2.5 2.5 0 0 1-2.5 2.5h-9l-4 4v-4H5A2.5 2.5 0 0 1 2.5 14V5.5A2.5 2.5 0 0 1 5 3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
