<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wr063mk4n"/><circle class="ht4-d0djo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:imaginary-i" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ht4-d0djo {
  cx: 12px;
  cy: 5.5px;
  r: 1.5px;
}

.wr063mk4n {
  d: path("M9.25 10H12v10m-3.25 0h6.5");
}

</style>
