<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="up5bnccaf"/><path class="oe_ries_t"/><circle class="tsn5jyb8z"/><path class="im52zfppb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:debt" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.im52zfppb {
  d: path("M16.31 13.04c-.25-.62-.93-1.08-1.71-1.08c-.99 0-1.71.56-1.71 1.33c0 1.77 3.56.99 3.56 2.88c0 .81-.78 1.36-1.86 1.36c-.84 0-1.55-.46-1.86-1.08");
}

.oe_ries_t {
  d: path("m6.59 6.59l3.14 3.14");
}

.tsn5jyb8z {
  cx: 14.5px;
  cy: 14.5px;
  r: 6.75px;
}

.up5bnccaf {
  cx: 5px;
  cy: 5px;
  r: 2.25px;
}

</style>
