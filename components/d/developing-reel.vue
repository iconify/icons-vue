<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0ovh-mnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:developing-reel" /></template>
<style>
.c0ovh-mnt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 12a2.75 2.75 0 0 1 5.5 0a4.125 4.125 0 0 1-8.25 0a5.5 5.5 0 0 1 11 0a6.875 6.875 0 0 1-13.75 0a8.25 8.25 0 0 1 16.5 0");
}

</style>
