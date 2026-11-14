<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ne-zmeb0k"/><path class="mwjevvhpx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ad-click" /></template>
<style>
.mwjevvhpx {
  d: path("m11 21.5l-2.75-4C7.5 16.25 8.75 15 10 16l1.5 1.25V9.5a1.5 1.5 0 0 1 3 0v4.75l4.25.75c1.25.25 2 1.25 1.75 2.5l-.75 4m-11-16.25l1.5 1.5m7-1.5l-1.5 1.5");
}

.ne-zmeb0k {
  d: path("M9.75 12.5H4.5a2 2 0 0 1-2-2v-6a2 2 0 0 1 2-2h13a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2h-1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
