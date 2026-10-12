<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mw9rhxb_k"/><circle class="shea171ph"/><path class="c16yfd7oi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lyrics-sharp" /></template>
<style>
.c16yfd7oi {
  d: path("M16.75 13V7l1.75.75");
}

.mw9rhxb_k {
  d: path("M4.75 3.25h16.5v14H9.5L5.25 20.5v-3.25h-2.5v-14zm2 4.25h6m-6 3.5h4");
}

.shea171ph {
  cx: 15.25px;
  cy: 13px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
