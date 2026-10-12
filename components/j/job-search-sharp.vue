<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="blf91sbrf"/><circle class="c1myp4vea"/><path class="a0x7qs0dl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:job-search-sharp" /></template>
<style>
.a0x7qs0dl {
  d: path("m18.25 18l3 3");
}

.blf91sbrf {
  d: path("M10.25 17.25h-7.5V6.75h15v3.5m-10-3.5v-3h5.5v3");
}

.c1myp4vea {
  cx: 16px;
  cy: 15.75px;
  r: 3px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
