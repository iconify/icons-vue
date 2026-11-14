<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g6ulkabjn"/><path class="a02n3-jcb"/><path class="k5om1hbaz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:carpet-area" /></template>
<style>
.a02n3-jcb {
  d: path("M5.5 5.5h13v13h-13ZM8 12h8");
}

.g6ulkabjn {
  d: path("M2.5 2.5h19v19h-19Z");
}

.k5om1hbaz {
  d: path("m10 10l-2 2l2 2m4-4l2 2l-2 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
