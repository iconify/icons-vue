<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vocin3ocp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:constellation" /></template>
<style>
.vocin3ocp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 7a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm4 9a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm4.5-4.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM15 18a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm4-10a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM4 8.5l3 6m1.5.5l2.5-2.5m1.75.25l3 4M17 16.5l3-7");
}

</style>
