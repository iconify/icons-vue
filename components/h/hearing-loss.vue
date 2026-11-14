<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xp0i01brb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hearing-loss" /></template>
<style>
.xp0i01brb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.286 4.367C9.318 3.501 10.684 3 12.25 3c3.25 0 5.5 2.5 5.5 5.75c0 1.72-.587 2.853-1.332 3.767m-2.932 4.952c-.069.322-.144.664-.236 1.031c-.5 1.75-2 2.5-3.5 2.5c-2 0-3.5-1.5-3.5-3.5M3.5 3.5l17 17");
}

</style>
