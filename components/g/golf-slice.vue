<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rkmuiotvj"/><path class="a2z5s4bbj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:golf-slice" /></template>
<style>
.a2z5s4bbj {
  d: path("m14 3l2.5 2L14 7");
}

.rkmuiotvj {
  d: path("M9 18.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm2.5-5.75C9.5 9.5 8 5.5 16 5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
