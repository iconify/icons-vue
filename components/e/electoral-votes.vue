<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lsud0k17c"/><path class="f_6h9wcig"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:electoral-votes" /></template>
<style>
.f_6h9wcig {
  d: path("m9.75 7.5l1.75 1.75l2.75-3");
}

.lsud0k17c {
  d: path("M3 12h18v9.5H3Zm4.5 0V3.5a1 1 0 0 1 1-1h7a1 1 0 0 1 1 1V12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
