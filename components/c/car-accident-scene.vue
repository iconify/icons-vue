<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zm35c7ipg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:car-accident-scene" /></template>
<style>
.zm35c7ipg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.417 8.595l2.394 6.914a1.5 1.5 0 0 1-1.418 1.991H9.607a1.5 1.5 0 0 1-1.418-1.991l2.394-6.914a1.5 1.5 0 0 1 2.834 0M5 20.5h14M9.75 11h4.5");
}

</style>
