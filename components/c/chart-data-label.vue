<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u83h24b3i"/><path class="ddeg8icyi"/><path class="g-9lg4bgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-data-label" /></template>
<style>
.ddeg8icyi {
  fill: currentColor;
  d: path("M3.5 21.5v-6h3v6Zm7 0v-9h3v9Zm7 0v-12h3v12Z");
}

.g-9lg4bgy {
  d: path("M16.5 2.5H20A1.5 1.5 0 0 1 21.5 4v1A1.5 1.5 0 0 1 20 6.5l-1 1.25l-1-1.25h-1.5A1.5 1.5 0 0 1 15 5V4a1.5 1.5 0 0 1 1.5-1.5Z");
}

.u83h24b3i {
  d: path("M2.5 21.5h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
