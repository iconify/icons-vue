<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="x104u3typ"/><path class="v4x61_bja"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:carnival-mask-sharp" /></template>
<style>
.v4x61_bja {
  d: path("M5.5 11.5c1.25-1.25 3-1.25 4.25 0c-1.25 1.25-3 1.25-4.25 0Zm8.75 0c1.25-1.25 3-1.25 4.25 0c-1.25 1.25-3 1.25-4.25 0Zm3.65 4.9l1.6 4.85");
}

.x104u3typ {
  d: path("m12.38 3.08l1.24 1.09l.38.33l-.38.33l-1.24 1.09l-.38.33l-.38-.33l-1.24-1.09L10 4.5l.38-.33l1.24-1.09l.38-.33zM2.75 8.5c3-1 6.25-.75 9.25 1c3-1.75 6.25-2 9.25-1c0 4.5-2.25 7.25-5.25 7.25c-1.75 0-3-1-4-2.5c-1 1.5-2.25 2.5-4 2.5c-3 0-5.25-2.75-5.25-7.25Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
