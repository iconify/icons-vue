<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-ojocmuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:graduated-cylinder" /></template>
<style>
.z-ojocmuq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 2.5h1.5v16L7 21h10l-2.5-2.5v-16M9.5 7h2.25M9.5 10.5h2.25M9.5 14h2.25");
}

</style>
