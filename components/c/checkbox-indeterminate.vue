<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcye7ub2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:checkbox-indeterminate" /></template>
<style>
.qcye7ub2i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 4h5.5A5.25 5.25 0 0 1 20 9.25v5.5A5.25 5.25 0 0 1 14.75 20h-5.5A5.25 5.25 0 0 1 4 14.75v-5.5A5.25 5.25 0 0 1 9.25 4M8 12h8");
}

</style>
