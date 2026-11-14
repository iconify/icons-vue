<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eo9bmobow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:archive-boxes" /></template>
<style>
.eo9bmobow {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.125 3h7.75A2.625 2.625 0 0 1 18.5 5.625v3.75A2.625 2.625 0 0 1 15.875 12h-7.75A2.625 2.625 0 0 1 5.5 9.375v-3.75A2.625 2.625 0 0 1 8.125 3m-2 9h11.75a2.625 2.625 0 0 1 2.625 2.625v3.75A2.625 2.625 0 0 1 17.875 21H6.125A2.625 2.625 0 0 1 3.5 18.375v-3.75A2.625 2.625 0 0 1 6.125 12M10 7.5h4m-4 9h4");
}

</style>
