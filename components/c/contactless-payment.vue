<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uz7-9bcsc"/><path class="pl0jav50w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:contactless-payment" /></template>
<style>
.pl0jav50w {
  d: path("M10.121 9.879a3 3 0 0 1 0 4.242m2.475-5.978a6 6 0 0 1 0 7.714");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uz7-9bcsc {
  d: path("M2.5 5h19v14h-19ZM8 12h.01");
}

</style>
