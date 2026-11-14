<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s-f7cfb-n"/><path class="dfxv_6-0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:company-holiday" /></template>
<style>
.dfxv_6-0e {
  d: path("m4.25 3.25l3 1L5.5 7.5ZM9 4.5l3 .25l-1.5 3.5Zm3 .25l3-.25l-1.5 3.75Zm4.75-.5l3-1L18.5 7.5Z");
}

.s-f7cfb-n {
  d: path("M8 11.25h8V21.5H8Zm5.75 5.25h.01M2.5 2.5q9.5 4.5 19 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
