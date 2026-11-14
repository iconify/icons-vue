<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q5q4_bbdl"/><path class="ke3z5xabi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:home-star" /></template>
<style>
.ke3z5xabi {
  d: path("m12 10.5l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291L12 15.75l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

.q5q4_bbdl {
  d: path("m4 10.5l8-7l8 7V20H4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
