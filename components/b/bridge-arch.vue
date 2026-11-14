<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4ibumbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bridge-arch" /></template>
<style>
.l4ibumbku {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h19v10h-3a6.5 6.5 0 0 0-13 0h-3Zm0 14.5q2.25-2 4.5 0t4.5 0t4.5 0t4.5 0");
}

</style>
