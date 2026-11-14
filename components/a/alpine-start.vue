<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdyt1ic-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:alpine-start" /></template>
<style>
.sdyt1ic-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5L9.5 7l4.5 8l2.25-2l5.25 7.5ZM18.75 3.75a3.5 3.5 0 1 0 2 4.5a2.75 2.75 0 0 1-2-4.5Z");
}

</style>
