<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qmvt8fbnf"/><path class="ey5a1cbqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:compound-growth-sharp" /></template>
<style>
.ey5a1cbqn {
  d: path("M6.5 17.25c5.5-.25 10-3.75 12.75-13m-2.53 1.1l2.53-1.1l1.1 2.53");
}

.qmvt8fbnf {
  d: path("M3.25 3.25v17.5h17.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
