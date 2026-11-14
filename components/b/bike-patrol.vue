<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="flh-jub3w"/><path class="lclax7bjt"/><path class="l2-xwsb2f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bike-patrol" /></template>
<style>
.flh-jub3w {
  d: path("M2.25 10a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Zm12 0a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Z");
}

.l2-xwsb2f {
  d: path("M16.75 3H15l3 7m-2.5 11.5h6m-5.25 0V19a2.25 2.25 0 0 1 4.5 0v2.5");
}

.lclax7bjt {
  d: path("m6 10l3-5.25h6.75L12 10Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
