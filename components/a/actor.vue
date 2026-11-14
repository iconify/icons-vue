<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rxe02f0aj"/><path class="ofa8umxpj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:actor" /></template>
<style>
.ofa8umxpj {
  d: path("M6 9q1.75-2.5 3.5 0m3 0q1.75-2.5 3.5 0m-8.5 4q.894.894 1.789 1.332m4.383-.602q.414-.316.828-.73m3.25 1l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

.rxe02f0aj {
  d: path("M12.87 18.747A7 7 0 0 1 11 19c-4 0-8-3.5-8-9V4q8-2.5 16 0v6l-.002.223");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
