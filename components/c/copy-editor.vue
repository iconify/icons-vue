<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8_8hcc3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:copy-editor" /></template>
<style>
.r8_8hcc3o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5H11A3.5 3.5 0 0 1 14.5 6v12a3.5 3.5 0 0 1-3.5 3.5H6.5A3.5 3.5 0 0 1 3 18V6a3.5 3.5 0 0 1 3.5-3.5M6 8h5.5M6 12h5.5M6 16h3.5m8-11.5a1.5 1.5 0 0 1 3 0v13l-1.5 3l-1.5-3Z");
}

</style>
