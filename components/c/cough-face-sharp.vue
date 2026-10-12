<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="d6l0dqbla"/><path class="jbner7bbd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cough-face-sharp" /></template>
<style>
.d6l0dqbla {
  cx: 10.25px;
  cy: 12px;
  r: 7.5px;
}

.jbner7bbd {
  d: path("M6.75 8.75L8.5 10l-1.75 1.25m7-2.5L12 10l1.75 1.25m-1.5 2.5a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 1 1 0-2.5ZM19.5 15h1.75m-2-2.75L21 11m-1.75 6.75L21 19");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
