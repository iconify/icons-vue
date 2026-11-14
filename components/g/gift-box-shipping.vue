<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xvcfkmbtk"/><path class="ii_5gqsqp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:gift-box-shipping" /></template>
<style>
.ii_5gqsqp {
  d: path("M3 7h18v3.5H3Zm9 0v13m0-13c-2-3.5-5-3.5-4-1c.5 1 2 1 4 1Zm0 0c2-3.5 5-3.5 4-1c-.5 1-2 1-4 1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xvcfkmbtk {
  d: path("M4 10h16v10H4Z");
}

</style>
