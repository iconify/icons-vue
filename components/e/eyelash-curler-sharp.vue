<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="udf-_vjyz"/><circle class="oiwecpbpf"/><circle class="p_frypbys"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eyelash-curler-sharp" /></template>
<style>
.oiwecpbpf {
  cx: 8.5px;
  cy: 18.5px;
  r: 2.75px;
}

.p_frypbys {
  cx: 15.5px;
  cy: 18.5px;
  r: 2.75px;
}

.udf-_vjyz {
  d: path("M5.5 3c4.3 1.5 8.7 1.5 13 0M3.25 7h17.5c-1.6 3.25-4.8 5-8.75 5s-7.15-1.75-8.75-5Zm6.25 5L9 15.75M14.5 12l.5 3.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
