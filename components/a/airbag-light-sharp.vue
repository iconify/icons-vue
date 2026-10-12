<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="rcl5bg80n"/><path class="ynv-g5b1r"/><circle class="c7ai1sd8z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:airbag-light-sharp" /></template>
<style>
.c7ai1sd8z {
  cx: 17.25px;
  cy: 7.5px;
  r: 3.75px;
}

.rcl5bg80n {
  cx: 7.75px;
  cy: 5px;
  r: 2.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ynv-g5b1r {
  d: path("M6.75 9.75h3l.23.97l.54 2.31l.23.97H16l.17.99l.91 5.27l.17.99h-3l-.23-.97l-.54-2.31l-.23-.97H7.5l-.28-.96l-1.19-4.08l-.28-.96V9.75z");
}

</style>
