<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e8tw6fbis"/><path class="j0v7rxb7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:litmus-blue" /></template>
<style>
.e8tw6fbis {
  d: path("M3.5 12h2v7A2.5 2.5 0 0 0 8 21.5h8a2.5 2.5 0 0 0 2.5-2.5v-7h2");
}

.j0v7rxb7q {
  fill: currentColor;
  d: path("M10 2.5h4V18h-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
