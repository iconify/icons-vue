<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3ldnswej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dam" /></template>
<style>
.c3ldnswej {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.59 20.5l1.82-15.75q.09-.75.84-.75h1.5q.75 0 1.06.68l7.13 15.89q.31.68-.44.68H9.25q-.75 0-.66-.75m2.16-8H16M10.25 17H18M2.75 7.75c1.3 0 1.3-.75 2.6-.75s1.3.75 2.6.75m-5.2 4c1.3 0 1.3-.75 2.6-.75s1.3.75 2.6.75m-5.2 4c1.3 0 1.3-.75 2.6-.75s1.3.75 2.6.75");
}

</style>
