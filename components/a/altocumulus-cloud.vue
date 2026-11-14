<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5j9shb6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:altocumulus-cloud" /></template>
<style>
.x5j9shb6k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10.5a2.75 2.75 0 0 1 5.5 0a3.25 3.25 0 1 1 5.5 0a2.75 2.75 0 0 1 5.5 0Zm2 8a2.75 2.75 0 0 1 5.5 0a3.25 3.25 0 1 1 5.5 0a2.75 2.75 0 0 1 5.5 0Z");
}

</style>
