<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4tw-6bgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lassi-glass" /></template>
<style>
.y4tw-6bgv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 9.25h9.5L15.6 20.1a1.25 1.25 0 0 1-1.25 1.15h-4.7A1.25 1.25 0 0 1 8.4 20.1Zm-.5 0a2 2 0 0 1 2-3a2.75 2.75 0 0 1 5.25-.5a2.2 2.2 0 0 1 3.25 3.5Zm1.75 4h7");
}

</style>
