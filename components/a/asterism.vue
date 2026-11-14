<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p274q_bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:asterism" /></template>
<style>
.p274q_bwy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 3l1.25 3h3L14 8l.75 3.25L12 9.5l-2.75 1.75L10 8L7.75 6h3ZM6.5 13.5l1 2.5l2.75.25l-2 1.75l.5 2.75l-2.25-1.5l-2.25 1.5l.5-2.75l-2-1.75L5.5 16Zm11 0l1 2.5l2.75.25l-2 1.75l.5 2.75l-2.25-1.5l-2.25 1.5l.5-2.75l-2-1.75L16.5 16Z");
}

</style>
