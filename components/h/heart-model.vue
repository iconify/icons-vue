<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h9yufpsmk"/><path class="fk48yebxv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heart-model" /></template>
<style>
.fk48yebxv {
  d: path("M13.5 7.25V5.5a2.25 2.25 0 0 1 4.5 0v1");
}

.h9yufpsmk {
  d: path("M7 9c-2 2-2 6 1 9q2.25 2.25 4.5 3c3-1.5 6.5-5 6.5-9.5c0-3-2-4.5-4-4.5c-1.25 0-2.25.5-3 1.25c-1-1-3.5-.75-5 .75Zm2.5-1V3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
