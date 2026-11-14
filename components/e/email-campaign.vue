<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zgqgox79d"/><path class="l4w-aw1pr"/><path class="n24bspbit"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:email-campaign" /></template>
<style>
.l4w-aw1pr {
  d: path("M2.5 8h15v11h-15Z");
}

.n24bspbit {
  d: path("m2.5 10l7.5 4.5l7.5-4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zgqgox79d {
  d: path("M6.5 8V6a2 2 0 0 1 2-2h11a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2h-2");
}

</style>
