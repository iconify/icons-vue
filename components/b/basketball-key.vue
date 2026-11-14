<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xcoi850ki"/><path class="ivzpdhhtj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:basketball-key" /></template>
<style>
.ivzpdhhtj {
  d: path("M15.25 15.25q2.75 2.75 0 5.5m5.5-5.5q-2.75 2.75 0 5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xcoi850ki {
  d: path("M3 8a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm9 0h9m-3 0v3m3-3v2.5M14 18a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm0 0h8");
}

</style>
