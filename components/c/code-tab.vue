<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="swumzpbwb"/><path class="vnsoh5bdj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:code-tab" /></template>
<style>
.swumzpbwb {
  d: path("M14.3 21.5H4.5v-19h15v8.7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vnsoh5bdj {
  d: path("M10 6.5L7.5 9l2.5 2.5m4-5L16.5 9L14 11.5m-.5 6.25H20M17.25 15L20 17.75l-2.75 2.75M22 14v7.5");
}

</style>
