<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-emqe_de"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cardinal-mark-west" /></template>
<style>
.j-emqe_de {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 2.5h8.5L12 5.75L16.25 9h-8.5L12 5.75ZM12 9v3m-4.75 4.75a4.75 4.75 0 1 0 9.5 0a4.75 4.75 0 1 0-9.5 0");
}

</style>
