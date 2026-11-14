<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sb4k1ybeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:divorce" /></template>
<style>
.sb4k1ybeb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14a4 4 0 1 0 8 0a4 4 0 1 0-8 0m15-4a4 4 0 0 1 0 8a4 4 0 0 1 0-8l-2-3l1-1.5h2l1 1.5Z");
}

</style>
