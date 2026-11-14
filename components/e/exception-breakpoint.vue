<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="upf3uubzm"/><path class="h_1b_fbrl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:exception-breakpoint" /></template>
<style>
.h_1b_fbrl {
  fill: currentColor;
  d: path("M17 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.upf3uubzm {
  d: path("m6.293 2.05l5.657 5.657a1 1 0 0 1 0 1.414L9.121 11.95a1 1 0 0 1-1.414 0L2.05 6.293a1 1 0 0 1 0-1.414L4.879 2.05a1 1 0 0 1 1.414 0Zm10 10l5.657 5.657a1 1 0 0 1 0 1.414l-2.829 2.829a1 1 0 0 1-1.414 0l-5.657-5.657a1 1 0 0 1 0-1.414l2.829-2.829a1 1 0 0 1 1.414 0ZM10 14l-1.5 1.5M14 10l1.5-1.5");
}

</style>
