<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m6zzohblj"/><path class="hzg4plbih"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:astronaut-tether" /></template>
<style>
.hzg4plbih {
  d: path("M16.5 11.5c3 0 5 2 5 4.5c0 3.5-2.75 5.5-5.5 5.5M6 9.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

.m6zzohblj {
  d: path("M2.5 15V9.5a7 7 0 0 1 14 0V15m-14 0h14v3.5h-14Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
