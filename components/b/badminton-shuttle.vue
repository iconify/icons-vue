<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l894-tb2h"/><path class="j4g21fbob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:badminton-shuttle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j4g21fbob {
  d: path("M9 15.5h6v2.75a3 3 0 0 1-6 0Z");
}

.l894-tb2h {
  d: path("M6.75 2.75h10.5q1 0 .75.97l-2.75 10.81q-.25.97-1.25.97h-4q-1 0-1.25-.97L6 3.72q-.25-.97.75-.97M12 15.5V2.75m-5.15 4.5h10.3");
}

</style>
