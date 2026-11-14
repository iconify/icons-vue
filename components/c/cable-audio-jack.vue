<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n33sysb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cable-audio-jack" /></template>
<style>
.n33sysb9w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5V8m0 0za2.5 2.5 0 0 1 2.5 2.5V13a2.5 2.5 0 0 1-2.5 2.5A2.5 2.5 0 0 1 9.5 13v-2.5A2.5 2.5 0 0 1 12 8m0 7.5V18a2.5 2.5 0 0 1-2.5 2.5h-5m6.25-16.25h2.5m-2.5 2h2.5");
}

</style>
