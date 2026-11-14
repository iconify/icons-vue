<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ziivanb6o"/><path class="laivgmbga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:drought-cracked-earth" /></template>
<style>
.laivgmbga {
  d: path("m11.5 6l-1 4l2 3l-1.5 5m1.5-5l4-1.5l3.25.5m-9.25-2L7 11.5l-2.75.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ziivanb6o {
  d: path("M6 6h15.5L18 18H2.5Z");
}

</style>
