<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nr2fehbzj"/><path class="qwwmhdber"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:machete" /></template>
<style>
.nr2fehbzj {
  d: path("M8.75 13.25L18.5 3.5c1.5-1.5 3-1 2.75 1.25C19.5 9.25 15 13 11 15.5Zm-1-1l4 4");
}

.qwwmhdber {
  d: path("m8.737 12.788l2.475 2.475l-4.949 4.949l-2.475-2.475Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
