<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgo9j8bcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:carbon-nanotube" /></template>
<style>
.hgo9j8bcg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a2 7 0 1 0 4 0a2 7 0 1 0-4 0Zm2-7h15m-15 14h15m0-14a2 7 0 0 1 0 14M17 12l-1.75 3h-3.5L10 12l1.75-3h3.5Z");
}

</style>
