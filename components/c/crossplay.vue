<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3ax98b_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crossplay" /></template>
<style>
.n3ax98b_q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 2.5h5.75A2.625 2.625 0 0 1 13.5 5.125v2.75a2.625 2.625 0 0 1-2.625 2.625h-5.75A2.625 2.625 0 0 1 2.5 7.875v-2.75A2.625 2.625 0 0 1 5.125 2.5M5.5 13.25h5m7.125-2.75h1.25a2.625 2.625 0 0 1 2.625 2.625v5.75a2.625 2.625 0 0 1-2.625 2.625h-1.25A2.625 2.625 0 0 1 15 18.875v-5.75a2.625 2.625 0 0 1 2.625-2.625m-1.375-6q2 0 2 3M16.75 6l1.5 1.5l1.5-1.5m-7.5 13.5q-6.75 0-6.75-3M4 18l1.5-1.5L7 18");
}

</style>
