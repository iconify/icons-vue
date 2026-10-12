<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fhv_i1dyu"/><path class="hrvutac1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:honey-jar-sharp" /></template>
<style>
.fhv_i1dyu {
  d: path("M6.5 2.75h11v3h-11zm1 3h9V7.5l2.25 1.125V21.25H5.25V8.625L7.5 7.5Z");
}

.hrvutac1o {
  d: path("m14.17 16.5l-1.74 1l-.43.25l-.43-.25l-1.74-1l-.43-.25v-3l.43-.25l1.74-1l.43-.25l.43.25l1.74 1l.43.25v3z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
