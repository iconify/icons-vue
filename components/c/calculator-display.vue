<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q0f-lgkcm"/><path class="f4v7pd0un"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:calculator-display" /></template>
<style>
.f4v7pd0un {
  d: path("M8 5.5h8v4H8Zm1 8.75h.01m5.99 0h.01M9 18h.01M15 18h.01");
}

.q0f-lgkcm {
  d: path("M5 2.5h14v19H5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
