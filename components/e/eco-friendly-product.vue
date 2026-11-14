<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mpsvl254q"/><path class="k3dqa5bwv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eco-friendly-product" /></template>
<style>
.k3dqa5bwv {
  d: path("M7.5 17.75C7.5 13 10 10 16.5 10c0 5-3 7.75-9 7.75Zm0 0l4.25-4.25");
}

.mpsvl254q {
  d: path("M2.5 2.5h19V7h-19ZM4 7v12.5q0 1 1 1h14q1 0 1-1V7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
