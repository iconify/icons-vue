<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy0pjvecl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:colour-checker" /></template>
<style>
.dy0pjvecl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 6.25h1A1.75 1.75 0 0 1 7 8v1a1.75 1.75 0 0 1-1.75 1.75h-1A1.75 1.75 0 0 1 2.5 9V8a1.75 1.75 0 0 1 1.75-1.75m7.25 0h1A1.75 1.75 0 0 1 14.25 8v1a1.75 1.75 0 0 1-1.75 1.75h-1A1.75 1.75 0 0 1 9.75 9V8a1.75 1.75 0 0 1 1.75-1.75m7.25 0h1A1.75 1.75 0 0 1 21.5 8v1a1.75 1.75 0 0 1-1.75 1.75h-1A1.75 1.75 0 0 1 17 9V8a1.75 1.75 0 0 1 1.75-1.75M4.25 13.5h1A1.75 1.75 0 0 1 7 15.25v1A1.75 1.75 0 0 1 5.25 18h-1a1.75 1.75 0 0 1-1.75-1.75v-1a1.75 1.75 0 0 1 1.75-1.75m7.25 0h1a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 12.5 18h-1a1.75 1.75 0 0 1-1.75-1.75v-1a1.75 1.75 0 0 1 1.75-1.75m7.25 0h1a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 19.75 18h-1A1.75 1.75 0 0 1 17 16.25v-1a1.75 1.75 0 0 1 1.75-1.75");
}

</style>
