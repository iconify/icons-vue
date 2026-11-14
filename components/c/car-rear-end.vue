<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e463ggkqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:car-rear-end" /></template>
<style>
.e463ggkqc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16v-3.5l2-1l1.5-3h2.5l1.25 3l.25 1V16Zm12 0v-3.5l1.5-1l1.25-3h2.25l1.5 3l.5 1V16Zm-11 2a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM17 18a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-4.75-9l.383 1.076l1.031-.49l-.49 1.031L14.25 11l-1.076.383l.49 1.031l-1.031-.49L12.25 13l-.383-1.076l-1.031.49l.49-1.031L10.25 11l1.076-.383l-.49-1.031l1.031.49Z");
}

</style>
