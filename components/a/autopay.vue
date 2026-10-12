<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="drmrwvbgh"/><path class="ewcswu75x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:autopay" /></template>
<style>
.drmrwvbgh {
  cx: 10px;
  cy: 14.25px;
  r: 6.75px;
}

.ewcswu75x {
  d: path("M11.81 12.79c-.25-.62-.93-1.08-1.71-1.08c-.99 0-1.71.56-1.71 1.33c0 1.77 3.56.99 3.56 2.88c0 .81-.78 1.36-1.86 1.36c-.84 0-1.55-.46-1.86-1.08M20.5 2.75l-2.75 3.5H21L18.75 9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
