<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tj67z-bgg"/><path class="kyhg65ggd"/><path class="zmkdfnmhj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:contrast-check" /></template>
<style>
.kyhg65ggd {
  d: path("M9 9h12v12H9Z");
}

.tj67z-bgg {
  fill: currentColor;
  d: path("M3 3h10v10H3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zmkdfnmhj {
  d: path("M14.5 16.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

</style>
