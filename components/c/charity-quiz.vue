<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g27uo5bko"/><path class="s-loqsb3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:charity-quiz" /></template>
<style>
.g27uo5bko {
  d: path("M12 3.5c5 0 8.5 3 8.5 7.25S17 18 12 18c-1.25 0-2.25-.15-3.25-.5L4.5 20l1-4c-1.5-1.5-2-3.25-2-5.25C3.5 6.5 7 3.5 12 3.5Z");
}

.s-loqsb3k {
  d: path("M9.75 8.5A2.25 2.25 0 1 1 12 10.75V12m0 2.75h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
