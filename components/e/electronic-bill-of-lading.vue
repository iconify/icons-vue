<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xt98kw-dg"/><path class="tm0w35jrr"/><path class="w1w4sfboj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:electronic-bill-of-lading" /></template>
<style>
.tm0w35jrr {
  d: path("M9 6.25h4l2 2v5H9Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w1w4sfboj {
  d: path("M13 6.25v2h2");
}

.xt98kw-dg {
  d: path("M3.5 3.5h17V16h-17Zm-1 16h19");
}

</style>
