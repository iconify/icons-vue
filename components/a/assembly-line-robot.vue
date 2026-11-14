<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exc2w3bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:assembly-line-robot" /></template>
<style>
.exc2w3bko {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5H7m-2 0v-6m1-3.75l3.5-5M12.25 6L17 8.75m-1.75 2v-2h3.5v2M3 13.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0M8.5 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m3 13.5H20a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-8.5A1.5 1.5 0 0 1 10 20a1.5 1.5 0 0 1 1.5-1.5m4.5-5h2a1.5 1.5 0 0 1 1.5 1.5v2a1.5 1.5 0 0 1-1.5 1.5h-2a1.5 1.5 0 0 1-1.5-1.5v-2a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
