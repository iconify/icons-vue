<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdak_32-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:chain-reaction" /></template>
<style>
.jdak_32-g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7.25-5A1.75 1.75 0 1 0 14 7a1.75 1.75 0 1 0-3.5 0m0 10a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0M7 10.75L10.75 8M7 13.25L10.75 16M14 6.25l6.75-2.75M14 7.5l6.75 2m-6.75 7l6.75-2M14 17.75l6.75 2.75");
}

</style>
