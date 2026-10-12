<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="v67nowbqx"/><circle class="g8q59cbpc"/><path class="ww2wt95xj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:best-seller-sharp" /></template>
<style>
.g8q59cbpc {
  cx: 7.5px;
  cy: 12px;
  r: 1.1px;
}

.v67nowbqx {
  d: path("M8.66 5.75h12.59v12.5H8.66l-.886-.002l-.594-.658l-3.86-4.25L2.111 12l1.209-1.34l3.86-4.25l.594-.658z");
}

.ww2wt95xj {
  d: path("m14.64 8.67l.82 1.84l.15.32l.34.04l2.01.21l.34.03l-.26.24l-1.49 1.35l-.26.23l.07.34l.42 1.97l.07.35l-.3-.18l-1.75-1.01l-.3-.17l-.3.17l-1.75 1.01l-.3.18l.07-.35l.42-1.97l.07-.34l-.26-.23l-1.49-1.35l-.26-.24l.34-.03l2.01-.21l.34-.04l.15-.32l.82-1.84l.14-.32z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
