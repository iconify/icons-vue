<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcfuz-b0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bike-park-jump" /></template>
<style>
.jcfuz-b0o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5c6.5 0 10-2 12-7v7m-12 0h19M13.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0m4 0h.01");
}

</style>
