<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iqo_56bgs"/><path class="btfdmp1lm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dental-filling" /></template>
<style>
.btfdmp1lm {
  d: path("M9.5 7.25h5v4h-5Z");
}

.iqo_56bgs {
  d: path("M5 3.5C3 3.5 3 6 3.5 9s2 4.5 2.5 6l1.5 5c.5 1 1.5.5 1.75-.5l1.25-5h3l1.25 5c.25 1 1.25 1.5 1.75.5l1.5-5c.5-1.5 2-3 2.5-6S21 3.5 19 3.5c-2.5 0-4 1-7 1s-4.5-1-7-1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
