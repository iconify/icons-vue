<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j61z0qavt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dose-night" /></template>
<style>
.j61z0qavt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 4a7 7 0 1 0 3.25 7.75A5.5 5.5 0 0 1 13 4m2.702 13.72l1.768-1.768a2 2 0 0 1 2.828 0a2 2 0 0 1 0 2.828l-1.768 1.768a2 2 0 0 1-2.828 0a2 2 0 0 1 0-2.828m.884-.884l2.828 2.828");
}

</style>
