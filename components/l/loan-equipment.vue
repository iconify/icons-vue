<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wnw482uzd"/><path class="g7vky-tem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:loan-equipment" /></template>
<style>
.g7vky-tem {
  d: path("M17 3h2a3 3 0 0 1 0 6h-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wnw482uzd {
  d: path("M6.5 6v11.9m-.3 1.6H2.5m6-4.1V12h11v3.4M10 12V8h1.5m-5 7h2m.5 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm6 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM14 6a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

</style>
