<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tuej1tmdy"/><path class="xa8p6o8-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dish-rack" /></template>
<style>
.tuej1tmdy {
  d: path("M2.5 15h19v5.5h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xa8p6o8-w {
  d: path("M5.5 10A1.25 5 0 1 0 8 10a1.25 5 0 1 0-2.5 0Zm5.25 0a1.25 5 0 1 0 2.5 0a1.25 5 0 1 0-2.5 0ZM16 10a1.25 5 0 1 0 2.5 0a1.25 5 0 1 0-2.5 0Z");
}

</style>
