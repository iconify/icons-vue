<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vl9jhmk6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:discovery" /></template>
<style>
.vl9jhmk6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 5.5q1.25 6.25 7.5 7.5q-6.25 1.25-7.5 7.5q-1.25-6.25-7.5-7.5q6.25-1.25 7.5-7.5ZM18 2q.5 2.5 3 3q-2.5.5-3 3q-.5-2.5-3-3q2.5-.5 3-3Zm1 14q.5 2 2.5 2.5q-2 .5-2.5 2.5q-.5-2-2.5-2.5q2-.5 2.5-2.5Z");
}

</style>
