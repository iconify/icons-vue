<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="m0ydh5bsj"/><circle class="mtl-gzbxy"/><circle class="t49y4h79e"/><path class="vrw5b6b7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:git-merge-check-sharp" /></template>
<style>
.m0ydh5bsj {
  cx: 6.75px;
  cy: 5.25px;
  r: 2.25px;
}

.mtl-gzbxy {
  cx: 6.75px;
  cy: 18.75px;
  r: 2.25px;
}

.t49y4h79e {
  cx: 17.25px;
  cy: 13.75px;
  r: 2.25px;
}

.vrw5b6b7q {
  d: path("M6.75 7.5v9m0-9c0 3.75 3 6.25 8.25 6.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
