<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k211y3brv"/><path class="nkbk1ob1c"/><path class="o_sf0d6sq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:git-branch-lock" /></template>
<style>
.k211y3brv {
  d: path("M3.75 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm11 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM6 7v14");
}

.nkbk1ob1c {
  d: path("M17 7c0 5.5-11 4.5-11 10m8 0h8v5h-8Z");
}

.o_sf0d6sq {
  d: path("M15.5 17v-1.25a2.5 2.5 0 0 1 5 0V17");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
