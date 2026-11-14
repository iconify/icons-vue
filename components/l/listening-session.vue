<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohfwdjbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:listening-session" /></template>
<style>
.ohfwdjbyf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 12.5v-2a3.75 3.75 0 0 1 7.5 0v2m-7.625 0za1.625 1.625 0 0 1 1.625 1.625v3.75A1.625 1.625 0 0 1 4.125 19.5A1.625 1.625 0 0 1 2.5 17.875v-3.75A1.625 1.625 0 0 1 4.125 12.5m7.75 0za1.625 1.625 0 0 1 1.625 1.625v3.75a1.625 1.625 0 0 1-1.625 1.625a1.625 1.625 0 0 1-1.625-1.625v-3.75a1.625 1.625 0 0 1 1.625-1.625M17.75 4H20a1.5 1.5 0 0 1 1.5 1.5V9a1.5 1.5 0 0 1-1.5 1.5h-1L16.25 13V5.5a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
