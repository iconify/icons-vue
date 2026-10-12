<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sg5wu1b-z"/><path class="ix4elus5l"/><rect class="i_xu-w8fj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:boxing-glove" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i_xu-w8fj {
  width: 10.5px;
  height: 3.25px;
  x: 5.75px;
  y: 18px;
  rx: 1.25px;
}

.ix4elus5l {
  d: path("M5.25 10H9.5a2.25 2.25 0 0 1 0 4.5");
}

.sg5wu1b-z {
  d: path("M5.25 15.5v-7A5.75 5.75 0 0 1 11 2.75h2.5a5.75 5.75 0 0 1 5.75 5.75v3a4 4 0 0 1-4 4Z");
}

</style>
