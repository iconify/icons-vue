<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mfr22jb8h"/><path class="vjzxndb7k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dinosaur-skull" /></template>
<style>
.mfr22jb8h {
  d: path("M3 12c0-4.75 3-7.5 7-7.5l7.5 2c2.5.75 3.5 2 3.5 4V12h-3l-1.25 2.75L15.5 12H12l-1.25 2.75L9.5 12Zm2 2.75q.5 5.75 5 5.75h9.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vjzxndb7k {
  d: path("M7 8.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

</style>
