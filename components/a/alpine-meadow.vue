<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m6se56bni"/><path class="i3hu9d5_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:alpine-meadow" /></template>
<style>
.i3hu9d5_g {
  d: path("M8.5 20q5.5-8.5 13-6m-7.75 3.25h.01m4.24 0h.01");
}

.m6se56bni {
  d: path("M2.5 20h19m-19 0L10 4l5 10");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
