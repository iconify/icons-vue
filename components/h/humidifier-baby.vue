<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ls4q55bqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:humidifier-baby" /></template>
<style>
.ls4q55bqb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.125 9.5h1.75a4.625 4.625 0 0 1 4.625 4.625a4.625 4.625 0 0 1-4.625 4.625h-1.75A4.625 4.625 0 0 1 6.5 14.125A4.625 4.625 0 0 1 11.125 9.5M5 21.5h14M8.5 6.75c-1-1.25 1-2.75 0-4.25M12 6.75C11 5.5 13 4 12 2.5m3.5 4.25c-1-1.25 1-2.75 0-4.25M12 14.25h.01");
}

</style>
