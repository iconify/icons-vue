<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ezknac2uj"/><path class="po6g1ib9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:embossing-stylus" /></template>
<style>
.ezknac2uj {
  d: path("M2.5 19h6a3.5 3.5 0 0 1 7 0h6");
}

.po6g1ib9v {
  d: path("M10.5 14a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm2.5-1l2.75-2.75m3.914-6.036l2.122 2.122l-4.95 4.95l-2.122-2.122Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
