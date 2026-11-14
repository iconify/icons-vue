<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4qvg7cru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:golf-driver" /></template>
<style>
.n4qvg7cru {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m20.5 2.5l-9 13m0 0c-3-1.25-8.5 0-8.5 3.25c0 2 2 2.75 5 2.75h3.5c1.25 0 1.75-1 1.25-2Zm5-11l2.75 2");
}

</style>
