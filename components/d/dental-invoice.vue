<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mg2-xhbke"/><path class="lz30_2b6s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dental-invoice" /></template>
<style>
.lz30_2b6s {
  d: path("M9.5 5c-1 0-1 1.5-.5 2.75l1 2.75l1-1.75h2l1 1.75l1-2.75c.5-1.25.5-2.75-.5-2.75s-1.5.5-2.5.5S10.5 5 9.5 5Zm-1 8.5h7m-7 3.25H13");
}

.mg2-xhbke {
  d: path("M5 2.5h14V21l-2.25-1.5L14.5 21L12 19.5L9.5 21l-2.25-1.5L5 21Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
