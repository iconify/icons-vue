<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qzgbw4b2d"/><path class="f9oz0xbko"/><path class="m86rgxj-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:delivery-porch" /></template>
<style>
.f9oz0xbko {
  d: path("M5.5 10.5h4.25v7H5.5Zm-2 7h17v3h-17ZM16 10l3.25 2v3.5l-3.25 2l-3.25-2V12Z");
}

.m86rgxj-i {
  d: path("M12.75 12L16 14l3.25-2M16 14v3.5");
}

.qzgbw4b2d {
  d: path("M2.5 9.5L12 2.75l9.5 6.75v8h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
