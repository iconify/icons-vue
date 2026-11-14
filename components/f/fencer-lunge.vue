<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pr3raxbrp"/><path class="a2vyczbel"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fencer-lunge" /></template>
<style>
.a2vyczbel {
  d: path("M9.5 6.5L10 13l-7 8.5m7-8.5l6 2v6.5m-6.25-12H15l6.5-3");
}

.pr3raxbrp {
  d: path("M7.5 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
