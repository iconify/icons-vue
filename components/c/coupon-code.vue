<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g0c7edc2n"/><path class="godd4zb6s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:coupon-code" /></template>
<style>
.g0c7edc2n {
  d: path("M4.5 5h15a2 2 0 0 1 2 2v2.5a2.5 2.5 0 0 0 0 5V17a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2v-2.5a2.5 2.5 0 0 0 0-5V7a2 2 0 0 1 2-2Z");
}

.godd4zb6s {
  d: path("M10 9.5L7.75 12L10 14.5m4-5l2.25 2.5L14 14.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
