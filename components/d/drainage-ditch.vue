<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p03gmbb3q"/><path class="znc2kx7qr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drainage-ditch" /></template>
<style>
.p03gmbb3q {
  d: path("M2 6.5h3l2.75 12h8.5L19 6.5h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.znc2kx7qr {
  d: path("M8.75 10.25q1.625-1.5 3.25 0t3.25 0m-5.5 4.5q1.125-1.5 2.25 0t2.25 0");
}

</style>
