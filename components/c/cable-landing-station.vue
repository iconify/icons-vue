<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbfn8bcmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cable-landing-station" /></template>
<style>
.rbfn8bcmi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.25 13.5h7.5a1.75 1.75 0 0 1 1.75 1.75v2A1.75 1.75 0 0 1 19.75 19h-7.5a1.75 1.75 0 0 1-1.75-1.75v-2a1.75 1.75 0 0 1 1.75-1.75M13 12V9.621a1.5 1.5 0 0 1 .439-1.06l2-2a1.5 1.5 0 0 1 2.122 0l2 2A1.5 1.5 0 0 1 20 9.621V12a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 13 12m-10.5-.5q1.5-1.5 3 0t3 0m-6 5.5h8");
}

</style>
