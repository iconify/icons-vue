<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xhat6845k"/><circle class="s9lus4bax"/><path class="dc0-cc4jx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:healing-brush-sharp" /></template>
<style>
.dc0-cc4jx {
  d: path("M7.25 14.5V19M5 16.75h4.5");
}

.s9lus4bax {
  cx: 7.25px;
  cy: 16.75px;
  r: 4.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xhat6845k {
  d: path("m11.13 8.87l1.44-1.44l.53-.53l.53.53l2.94 2.94l.53.53l-.53.53l-1.44 1.44l-.53.53l-.53-.53l-2.94-2.94l-.53-.53zm3.97.03l5.65-5.65");
}

</style>
