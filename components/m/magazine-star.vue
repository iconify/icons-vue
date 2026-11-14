<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jx26lzbqn"/><path class="r9g5c-cjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:magazine-star" /></template>
<style>
.jx26lzbqn {
  d: path("M4.5 2.5h15v19h-15Zm3 4h9");
}

.r9g5c-cjq {
  d: path("m12 9.5l1.25 2.75l3 .25L14 14.75l.75 3L12 16l-2.75 1.75l.75-3l-2.25-2.25l3-.25Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
