<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c1choybaa"/><path class="torou4wml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lunar-lantern" /></template>
<style>
.c1choybaa {
  d: path("M3.5 12a8.5 6.5 0 1 0 17 0a8.5 6.5 0 1 0-17 0Z");
}

.torou4wml {
  d: path("M9 3h6v2.5H9Zm3 15.5v3m0-16a3.5 6.5 0 0 0 0 13m0-13a3.5 6.5 0 0 1 0 13");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
