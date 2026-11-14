<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dtq_exuzk"/><path class="lmbmm56nt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:direct-debit" /></template>
<style>
.dtq_exuzk {
  d: path("M2.5 7.25L12 2.5l9.5 4.75Zm1 2.75h17m-18 10.25H13m-8-7.5v4.75m3.5-4.75v4.75m3.5-4.75v4.75m9.098-.5a3 3 0 1 1-2.598-1.5");
}

.lmbmm56nt {
  d: path("m17.25 14.25l1.25 1.25l-1.25 1.25");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
