<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xo3cpbb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chatbot-sparkle" /></template>
<style>
.xo3cpbb5h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 8.5h11.5a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1v-10a1 1 0 0 1 1-1Zm5.75 0V4.75M7.25 14h.01m4.99 0h.01m6.49-12q0 3.25 3.25 3.25q-3.25 0-3.25 3.25q0-3.25-3.25-3.25q3.25 0 3.25-3.25Z");
}

</style>
