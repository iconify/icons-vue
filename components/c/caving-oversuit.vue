<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f2l9bjblo"/><path class="h96mhob3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:caving-oversuit" /></template>
<style>
.f2l9bjblo {
  d: path("m8.5 3l-4 2L3 13l2.5.5l1.5-5V21h3.75L12 14l1.25 7H17V8.5l1.5 5L21 13l-1.5-8l-4-2Z");
}

.h96mhob3i {
  d: path("M8.5 3L12 6l3.5-3M12 6v5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
