<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_8f76bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:git-commits" /></template>
<style>
.f_8f76bfz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2v2.5m-2 2a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2 2v7m-2 2a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2 2V22");
}

</style>
