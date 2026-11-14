<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wp4unvb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lead-disqualified" /></template>
<style>
.wp4unvb-x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.534 20.5H5.5c-.6 0-1-.4-1-1c0-2.619 2.477-4.666 5.934-5.144m4.013-3.853q.25-.245.447-.534q.196-.289.332-.611q.136-.323.205-.666Q15.5 8.35 15.5 8q0-.172-.017-.343t-.05-.34t-.084-.333t-.115-.323q-.066-.159-.147-.311t-.177-.294q-.095-.143-.204-.276q-.11-.133-.231-.255q-.122-.121-.255-.231q-.133-.109-.276-.204q-.142-.096-.294-.177t-.311-.147q-.158-.065-.323-.115t-.333-.084q-.169-.033-.34-.05T12 4.5q-.351 0-.696.07q-.344.07-.668.207q-.323.136-.613.335q-.29.198-.535.451M3.5 3.5l17 17");
}

</style>
