<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="woqcq9rna"/><path class="ccxh-djip"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crop-top-sharp" /></template>
<style>
.ccxh-djip {
  d: path("M9.75 6.5a2.25 2.75 0 0 0 4.5 0M5.5 14.75h13");
}

.woqcq9rna {
  d: path("M8.07 6.87L4.93 8.13L4 8.5l-.2.98l-.35 1.79l-.2.98l.98.22l.29.06l.98.22v4.5h13v-4.5l.98-.22l.29-.06l.98-.22l-.2-.98l-.35-1.79l-.2-.98l-.93-.37l-3.14-1.26L15 6.5H9z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
