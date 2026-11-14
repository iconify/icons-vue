<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_b3x1bgy"/><path class="h18_52b9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:employee-survey" /></template>
<style>
.h18_52b9b {
  d: path("M9.449 11.625a2.25 2.25 0 0 1-3.898 0M15.25 7.75h.01m2.99 0h.01m-3.459 5.625a2.25 2.25 0 0 1 3.898 0");
}

.j_b3x1bgy {
  d: path("M4.5 3h15a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2H10l-4 3.5V17H4.5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2ZM12 6v8M6 7.75h.01m2.99 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
