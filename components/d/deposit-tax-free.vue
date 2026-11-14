<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o74my8bto"/><path class="zmkbbgdxp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deposit-tax-free" /></template>
<style>
.o74my8bto {
  d: path("M11.336 17.992A4.6 4.6 0 0 1 10 17.75v1.75H7.5V17C5.25 16 4 14.25 4 12c0-3.5 3.5-6 8-6c3.784 0 6.86 1.767 7.744 4.411");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zmkbbgdxp {
  d: path("M4.5 10.5h-2v3h2m3.25-2.75h.01M10.5 8.5h3m1.5 13l5.75-7.75m-6 .75a1 1 0 1 0 2 0a1 1 0 1 0-2 0ZM19 20.75a1 1 0 1 0 2 0a1 1 0 1 0-2 0Zm-4.75-4.5l7.5 3.25");
}

</style>
