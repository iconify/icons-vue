<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvntaobie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arepa" /></template>
<style>
.jvntaobie {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.363 11.962l13.274-4.424a1.74 1.74 0 0 0 1.113-2.163a1.66 1.66 0 0 0-2.113-1.087L4.363 8.712a1.74 1.74 0 0 0-1.113 2.163a1.66 1.66 0 0 0 2.113 1.087M4.75 16h14.5a2.25 2.25 0 0 1 2.25 2.25a2.25 2.25 0 0 1-2.25 2.25H4.75a2.25 2.25 0 0 1-2.25-2.25A2.25 2.25 0 0 1 4.75 16m1.75 0c0-1.5 1.75-2.25 3.5-1.75q3-1.5 6 0c1.75-.75 3.5 0 3.5 1.75");
}

</style>
