<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l8t0v3ktt"/><path class="lqsvcdcna"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:aisle-sign" /></template>
<style>
.l8t0v3ktt {
  d: path("M3 9h18v11H3Zm-.5-5.5h19M7 3.5V9m10-5.5V9M6.5 14.5h11");
}

.lqsvcdcna {
  d: path("m14.5 11.75l3 2.75l-3 2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
