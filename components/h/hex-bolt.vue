<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf1xi4bge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hex-bolt" /></template>
<style>
.cf1xi4bge {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 2.5h4.5A1.75 1.75 0 0 1 16 4.25v.5a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 8 4.75v-.5A1.75 1.75 0 0 1 9.75 2.5m.25 4v13a2 2 0 0 0 4 0v-13m-4 4l4-1m-4 4l4-1m-4 4l4-1");
}

</style>
