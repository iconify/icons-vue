<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ij4kqvlzv"/><circle class="ydy0opbpr"/><path class="jmv_-lb9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:birthday-kid-sharp" /></template>
<style>
.ij4kqvlzv {
  d: path("m8.42 11l3.18-7.1l.4-.9l.4.9l3.18 7.1a5.75 5.75 0 0 0-7.16 0Z");
}

.jmv_-lb9y {
  d: path("M9.75 14.25v.5m4.5-.5v.5m-4 2.75L12 19.075l1.75-1.575");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ydy0opbpr {
  cx: 12px;
  cy: 15.5px;
  r: 5.75px;
}

</style>
