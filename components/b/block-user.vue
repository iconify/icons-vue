<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="in9lc0b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:block-user" /></template>
<style>
.in9lc0b8c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0m-3 13c0-3.75 3-6.25 7-6.25c1.143 0 2.078 0 2.803.191M14.5 18a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m1-2.5l5 5");
}

</style>
