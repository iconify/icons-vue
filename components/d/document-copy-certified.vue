<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bhc1cv4vv"/><path class="tmpvgrbdw"/><path class="e9fltbcec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:document-copy-certified" /></template>
<style>
.bhc1cv4vv {
  d: path("M4.5 17V5A2.5 2.5 0 0 1 7 2.5h8");
}

.e9fltbcec {
  d: path("m14.75 18l2 2L21 15.75");
}

.tmpvgrbdw {
  d: path("M14.3 21.5H7.5V6h12v7.3m0 7.9v.3h-.3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
