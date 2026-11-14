<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pfifogrfy"/><path class="qb1b68cdy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hypothesis" /></template>
<style>
.pfifogrfy {
  d: path("M9 16.5c-1.75-1.25-3-3.25-3-5.5a6 6 0 0 1 12 0c0 2.25-1.25 4.25-3 5.5V18H9Zm1 4.5h4");
}

.qb1b68cdy {
  d: path("M10.5 9.75c0-1 .7-1.75 1.5-1.75s1.5.75 1.5 1.5c0 1.25-1.5 1.5-1.5 2.75m0 2.5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
