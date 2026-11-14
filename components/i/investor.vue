<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kp04-ibrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:investor" /></template>
<style>
.kp04-ibrb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20.5c0-3.25 2.25-5.25 4.75-5.25s4.5 2 4.5 5.25ZM17.625 11h1.25a2.625 2.625 0 0 1 2.625 2.625v4.25a2.625 2.625 0 0 1-2.625 2.625h-1.25A2.625 2.625 0 0 1 15 17.875v-4.25A2.625 2.625 0 0 1 17.625 11M4.25 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M15 14.25h6.5M15 17.5h6.5");
}

</style>
