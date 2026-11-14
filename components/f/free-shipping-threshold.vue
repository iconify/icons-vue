<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dx0awnbpp"/><path class="ddgznjxzo"/><path class="vrn0v7e-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:free-shipping-threshold" /></template>
<style>
.ddgznjxzo {
  d: path("M5.25 12.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm11 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

.dx0awnbpp {
  d: path("M2.5 2.5h12V11h-12Zm12 2.5H18l3.5 3.5V11h-7m-12 6.5h19v4h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vrn0v7e-i {
  fill: currentColor;
  d: path("M2.5 17.5h10v4h-10Z");
}

</style>
