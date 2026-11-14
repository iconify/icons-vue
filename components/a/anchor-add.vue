<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8_h8mbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:anchor-add" /></template>
<style>
.y8_h8mbmx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2 2V18m-4-8.5h8M2.5 12a6 6 0 0 0 12 0m3.5 3v6m-3-3h6");
}

</style>
