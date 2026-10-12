<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lmdvgdb3k"/><rect class="qbta1db8d"/><path class="a044cvc7m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:census" /></template>
<style>
.a044cvc7m {
  d: path("M10.5 10.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m-3.75 6.75a2.25 2.25 0 0 1 4.5 0Zm7-6.25h2.75m-2.75 3h2.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lmdvgdb3k {
  d: path("M14.75 4.25h2.5a2 2 0 0 1 2 2v13a2 2 0 0 1-2 2H6.75a2 2 0 0 1-2-2v-13a2 2 0 0 1 2-2h2.5");
}

.qbta1db8d {
  width: 5.5px;
  height: 3px;
  x: 9.25px;
  y: 2.75px;
  rx: 1px;
}

</style>
