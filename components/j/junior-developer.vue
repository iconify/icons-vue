<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_sczi9yj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:junior-developer" /></template>
<style>
.b_sczi9yj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0M2.5 21c0-4 3.5-6.5 7.5-6.5c.619 0 1.225.06 1.809.176M18 21.5v-5m0 1c0-2.5 1.5-3.5 3.5-3.5c0 2.5-1.5 3.5-3.5 3.5m0 1c0-2-1.5-3-3.5-3c0 2 1.5 3 3.5 3");
}

</style>
