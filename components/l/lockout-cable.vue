<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i6eu0oi1q"/><path class="gwrsbdbwc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lockout-cable" /></template>
<style>
.gwrsbdbwc {
  d: path("M14.75 14.5v-2.75a2.25 2.25 0 0 1 4.5 0v2.75m-6.75 0h9v7h-9Z");
}

.i6eu0oi1q {
  d: path("M6.5 15.5a7 7 0 1 1 10.5-6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
