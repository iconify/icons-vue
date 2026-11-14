<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wrcg6qhaf"/><path class="hapie2b-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:investigative-board" /></template>
<style>
.hapie2b-m {
  d: path("M6 15a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm9-6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-6.25 5.25l6.5-4.5M5.5 7.25h4v3h-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wrcg6qhaf {
  d: path("M2.5 4.5h19v15h-19Z");
}

</style>
