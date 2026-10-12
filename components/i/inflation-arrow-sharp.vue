<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="rbywe3b-o"/><path class="llj33hbot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:inflation-arrow-sharp" /></template>
<style>
.llj33hbot {
  d: path("m10.46 12.29l-.435-1.08H7.04v1.33c0 1.77 3.56.99 3.56 2.88v1.36H7.42l-.54-1.08m1.87-5.57v1.08m0 5.58v1.08m9.5 2.38v-16m-3 3l3-3l3 3");
}

.rbywe3b-o {
  cx: 8.75px;
  cy: 14px;
  r: 6px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
