<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kr71oacge"/><path class="xu68j4rdt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:event-loop" /></template>
<style>
.kr71oacge {
  d: path("M20 12.5a8 8 0 1 1-8-8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xu68j4rdt {
  d: path("M9.75 2.25L12 4.5L9.75 6.75m-1.25 3h7m-7 2.75h7m-7 2.75H13");
}

</style>
