<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jazqedwnx"/><path class="o6ephob7s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:alpha-particle" /></template>
<style>
.jazqedwnx {
  d: path("M3 10a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Z");
}

.o6ephob7s {
  d: path("M6 14a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm11.5-2h4m-2.25-2.25L21.5 12l-2.25 2.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
