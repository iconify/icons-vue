<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngffk966g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:layered-shot" /></template>
<style>
.ngffk966g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.713 5h10.574a1.5 1.5 0 0 1 1.487 1.698l-1.6 12A1.5 1.5 0 0 1 15.687 20H8.313a1.5 1.5 0 0 1-1.487-1.302l-1.6-12A1.5 1.5 0 0 1 6.713 5M5.5 9h13M6 12.75h12M6.5 16.5h11");
}

</style>
