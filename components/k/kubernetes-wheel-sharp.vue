<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ku6jh81wx"/><circle class="ons53cb4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kubernetes-wheel-sharp" /></template>
<style>
.ku6jh81wx {
  d: path("m13.58 3.26l4.27 2.06l1.58.76l.39 1.7l1.05 4.63l.39 1.7l-1.09 1.37l-2.96 3.71l-1.09 1.37H7.88l-1.09-1.37l-2.96-3.71l-1.09-1.37l.39-1.7l1.05-4.63l.39-1.7l1.58-.76l4.27-2.06L12 2.5zM12 8.25V5m2.93 4.66l2.54-2.02m-1.81 5.19l3.16.73m-5.19 1.82l1.41 2.93m-4.67-2.93l-1.41 2.93m-.62-5.48l-3.16.73m3.89-3.9L6.53 7.64");
}

.ons53cb4g {
  cx: 12px;
  cy: 12px;
  r: 2.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
