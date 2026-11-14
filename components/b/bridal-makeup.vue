<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckbh9qb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bridal-makeup" /></template>
<style>
.ckbh9qb7m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.625 12h2.75A2.625 2.625 0 0 1 13 14.625v4.25a2.625 2.625 0 0 1-2.625 2.625h-2.75A2.625 2.625 0 0 1 5 18.875v-4.25A2.625 2.625 0 0 1 7.625 12M6.5 12V6.5l5-3.5v9m4.5 7.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m1.637-4.137L17.75 15a1.06 1.06 0 0 1 1.5 0l.113.113a.74.74 0 0 1-.113 1.137a1.35 1.35 0 0 1-1.5 0a.74.74 0 0 1-.113-1.137");
}

</style>
