<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewbskx-bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:context-menu" /></template>
<style>
.ewbskx-bj {
  fill: currentColor;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m0 7a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m0 7a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
