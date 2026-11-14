<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ae92awdvc"/><path class="rzy4jubdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:diesel" /></template>
<style>
.ae92awdvc {
  d: path("M3.5 3H15v18.5H3.5ZM15 12.5h1.75a1 1 0 0 1 1 1V17a1.5 1.5 0 0 0 3 0V8l-2.5-2.5M6.5 8v8");
}

.rzy4jubdg {
  d: path("M6.5 8H8a4 4 0 0 1 0 8H6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
