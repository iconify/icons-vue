<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b1giyo3pl"/><path class="k1tddsuem"/><path class="l6siwif2y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:edit-square" /></template>
<style>
.b1giyo3pl {
  d: path("M6.875 2.5h10.25A4.375 4.375 0 0 1 21.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 17.125V6.875A4.375 4.375 0 0 1 6.875 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k1tddsuem {
  d: path("M16.596 7.404za1.5 1.5 0 0 1 0 2.121l-4.242 4.243a1.5 1.5 0 0 1-2.122 0a1.5 1.5 0 0 1 0-2.122l4.243-4.242a1.5 1.5 0 0 1 2.121 0");
}

.l6siwif2y {
  d: path("M10.232 13.768za.927.927 0 0 1-.362 1.535l-.168.056a.839.839 0 0 1-1.061-1.061l.056-.168a.927.927 0 0 1 1.535-.362");
}

</style>
