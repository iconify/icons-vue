<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfvlu3jcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cloud-hail" /></template>
<style>
.vfvlu3jcr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 15.5a4 4 0 0 1 0-8a5.5 5.5 0 0 1 11 1a3.5 3.5 0 0 1-1 7Zm-.5 4a1 1 0 1 0 2 0a1 1 0 1 0-2 0m4.5 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0m4.5 0a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>
