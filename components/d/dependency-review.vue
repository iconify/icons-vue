<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2pvfrbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dependency-review" /></template>
<style>
.f2pvfrbfp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3H10v7.5H2.5Zm10 13.5H12V9h7.5v4.6M6.25 10.5v2.25H12m2.5 5.75c1.75-3 5.25-3 7 0c-1.75 3-5.25 3-7 0Zm3.5 0h.01");
}

</style>
