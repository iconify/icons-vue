<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k666jfb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hotspot-sharp" /></template>
<style>
.k666jfb1l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 10.25h8v11H8zm2.75 8h2.5M10.59 7.09L12 5.688l1.41 1.402M8.46 4.96a5 5 0 0 1 7.08 0");
}

</style>
