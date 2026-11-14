<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hkswtgbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:campfire-marshmallow" /></template>
<style>
.hkswtgbsl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m18.96 4.26l.53.53a2.625 2.625 0 0 1 0 3.713L18.253 9.74a2.625 2.625 0 0 1-3.713 0l-.53-.53a2.625 2.625 0 0 1 0-3.713l1.237-1.237a2.625 2.625 0 0 1 3.713 0M3.5 20.25L14.25 9.5m4.25 12c-2 0-3.25-1.5-3.25-3.25s1.25-3 1.75-4.5c.75 1 1.25 1.75 1.5 2.75c.5-.75.75-1.25 1-1.75c1.25 1 2.25 2.25 2.25 3.75c0 1.75-1.5 3-3.25 3");
}

</style>
