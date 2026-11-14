<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uunfowbnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camp-coffee-press" /></template>
<style>
.uunfowbnj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.625 7h5.75A2.625 2.625 0 0 1 16 9.625v9.25a2.625 2.625 0 0 1-2.625 2.625h-5.75A2.625 2.625 0 0 1 5 18.875v-9.25A2.625 2.625 0 0 1 7.625 7M16 10h1.5a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2H16M10.5 2.5v11M8 2.5h5m-5.25 11h5.5");
}

</style>
