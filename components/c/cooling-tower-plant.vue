<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6i8icbsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cooling-tower-plant" /></template>
<style>
.n6i8icbsn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21q3-7 1-12h6q-2 5 1 12Zm11 0q3-7 1-12h6q-2 5 1 12ZM4 6.25a1.75 1.75 0 0 1 2.5-2a1.75 1.75 0 0 1 2.5 2m6 0a1.75 1.75 0 0 1 2.5-2a1.75 1.75 0 0 1 2.5 2");
}

</style>
