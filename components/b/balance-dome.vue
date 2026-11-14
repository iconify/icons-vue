<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vi4rwvjkb"/><path class="s8q_ybbid"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:balance-dome" /></template>
<style>
.s8q_ybbid {
  d: path("M6.5 10.5c3 1.5 8 1.5 11 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vi4rwvjkb {
  d: path("M4 15.5a8 8 0 0 1 16 0m-17.5 0h19V19h-19Z");
}

</style>
