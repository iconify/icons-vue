<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="c15actb7e"/><path class="ccqdf8ors"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:alms-bowl-sharp" /></template>
<style>
.c15actb7e {
  cx: 12px;
  cy: 4.5px;
  r: 1.5px;
}

.ccqdf8ors {
  d: path("M3.75 9C4.75 7 8 6 12 6s7.25 1 8.25 3Zm-.25 3h17c0 5.25-3.8 9.25-8.5 9.25s-8.5-4-8.5-9.25Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
