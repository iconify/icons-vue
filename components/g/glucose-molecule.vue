<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2zrejbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:glucose-molecule" /></template>
<style>
.y2zrejbfb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.744 8.925l3.75 2.143a1.5 1.5 0 0 1 .756 1.302v4.26a1.5 1.5 0 0 1-.756 1.302l-3.75 2.143a1.5 1.5 0 0 1-1.488 0l-3.75-2.143a1.5 1.5 0 0 1-.756-1.302v-4.26a1.5 1.5 0 0 1 .756-1.302l3.75-2.143a1.5 1.5 0 0 1 1.488 0M12 8.5V5.75M10.25 4a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m-3.5 13.5h.01");
}

</style>
