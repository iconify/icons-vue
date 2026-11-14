<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twef3nb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:magician-hat" /></template>
<style>
.twef3nb3p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.647 4.747l5.38-1.144a1.75 1.75 0 0 1 2.075 1.348l1.664 7.825a1.75 1.75 0 0 1-1.348 2.076l-5.38 1.143a1.75 1.75 0 0 1-2.076-1.348L6.299 6.822a1.75 1.75 0 0 1 1.348-2.075M5.392 16.983l14.672-3.119M3.5 19.75L20 9");
}

</style>
