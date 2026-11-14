<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c3r0iwb1n"/><path class="j_58beb3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:channel-up" /></template>
<style>
.c3r0iwb1n {
  d: path("M2.5 7.5h19V21h-19Zm5.5-5l4 5l4-5");
}

.j_58beb3y {
  d: path("m8.5 16l3.5-3.5l3.5 3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
