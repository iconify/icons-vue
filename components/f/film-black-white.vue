<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w-n_8gb3w"/><path class="i5r72ehqt"/><path class="mxhon2akf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:film-black-white" /></template>
<style>
.i5r72ehqt {
  fill: currentColor;
  d: path("M9.75 8h4.5v8h-4.5Z");
}

.mxhon2akf {
  d: path("M17 8h4.5v8H17Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w-n_8gb3w {
  d: path("M2.5 4.5h19m-19 15h19M2.5 8H7v8H2.5Z");
}

</style>
