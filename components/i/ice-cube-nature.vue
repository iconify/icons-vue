<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ve-r4rlol"/><path class="p-459hxus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ice-cube-nature" /></template>
<style>
.p-459hxus {
  d: path("M4 6.25L11 10l7-3.75M11 10v8m7.5-1s1.75 2 1.75 3a1.75 1.75 0 0 1-3.5 0c0-1 1.75-3 1.75-3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ve-r4rlol {
  d: path("m11 2.5l7 3.75v8L11 18l-7-3.75v-8Z");
}

</style>
