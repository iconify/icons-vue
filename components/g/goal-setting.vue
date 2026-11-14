<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dtnhfudyf"/><path class="pynywcbic"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:goal-setting" /></template>
<style>
.dtnhfudyf {
  d: path("M3 13a8 8 0 1 0 16 0a8 8 0 1 0-16 0Z");
}

.pynywcbic {
  d: path("M7.5 13a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm3.5 0l9-9m-2.5-1l3.25.25L21 6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
