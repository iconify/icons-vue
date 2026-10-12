<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="msr0d68qf"/><circle class="aoknrac1h"/><circle class="ryeuqv1om"/><path class="vpxg03izo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:intermodal-sharp" /></template>
<style>
.aoknrac1h {
  cx: 5.75px;
  cy: 18.5px;
  r: 1.75px;
}

.msr0d68qf {
  d: path("M6.5 4.25h11v7h-11zm3.67 0v7m3.66-7v7M2.75 14.5h18.5");
}

.ryeuqv1om {
  cx: 10.25px;
  cy: 18.5px;
  r: 1.75px;
}

.vpxg03izo {
  d: path("m14 19.25l1.75-1.458l1.75 1.458l1.875 1.563l1.875-1.563");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
