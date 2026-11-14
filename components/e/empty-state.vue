<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj6hy2bgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:empty-state" /></template>
<style>
.oj6hy2bgi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6.5v-2a2 2 0 0 1 2-2h2m3.5 0h4m3.5 0h2a2 2 0 0 1 2 2v2m0 3.5v4m0 3.5v2a2 2 0 0 1-2 2h-2m-3.5 0h-4m-3.5 0h-2a2 2 0 0 1-2-2v-2m0-3.5v-4m7 0h.01m4.99 0h.01M9 16.5c1.25-2.5 4.75-2.5 6 0");
}

</style>
