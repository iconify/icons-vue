<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f-5g8jbes"/><path class="ahtrtw8qp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dental-emergency" /></template>
<style>
.ahtrtw8qp {
  d: path("M9.5 3.25L8 6.5l2.5 2.25L9 11.5m9 3.25v3.5M18 21h.01");
}

.f-5g8jbes {
  d: path("M6 2.5C3.75 2.5 2.5 4.25 2.5 7c0 2.5 1.25 4.5 1.75 6.5L5 17.75c.25 1.5 2 1.5 2.25 0L8 14.5c.25-1 1.25-1 1.5 0l.75 3.25c.25 1.5 2 1.5 2.25 0l.75-4.25c.5-2 1.75-4 1.75-6.5c0-2.75-1.25-4.5-3.5-4.5c-1.25 0-1.75.75-2.75.75S7.25 2.5 6 2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
