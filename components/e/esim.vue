<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o-av9cbeg"/><path class="cfzsbyb4d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:esim" /></template>
<style>
.cfzsbyb4d {
  d: path("M8 10.5h8v8H8Zm4 0v8");
}

.o-av9cbeg {
  d: path("M5 4.5a2 2 0 0 1 2-2h7l5 5v12a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
