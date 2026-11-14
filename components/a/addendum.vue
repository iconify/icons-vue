<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gbxsp6p4c"/><path class="nlp70zbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:addendum" /></template>
<style>
.gbxsp6p4c {
  d: path("M4.5 2.5h9l5 5V17h-14Zm2 14.5v4.5H13V17");
}

.nlp70zbiv {
  d: path("M13.5 2.5v5h5M8 10.5h7m-7 3.25h4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
