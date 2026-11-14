<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_t5z2nvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arrow-big-left" /></template>
<style>
.n_t5z2nvh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.356 10.144l4.553-4.553a.932.932 0 0 1 1.591.659a2.25 2.25 0 0 0 2.25 2.25h4.125a2.625 2.625 0 0 1 2.625 2.625v1.75a2.625 2.625 0 0 1-2.625 2.625H13.75a2.25 2.25 0 0 0-2.25 2.25a.932.932 0 0 1-1.591.659l-4.553-4.553a2.625 2.625 0 0 1 0-3.712");
}

</style>
