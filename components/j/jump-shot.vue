<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="depprosxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:jump-shot" /></template>
<style>
.depprosxk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 9.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m-3 12V18q0-3.5 3.5-3.5h4q3.5 0 3.5 3.5v3.5m-2-7L16 7m-1-2a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
