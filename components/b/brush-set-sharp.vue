<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vlqa4vrkv"/><circle class="eiufiabtg"/><circle class="h8r22mm8a"/><path class="wat16xbbe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:brush-set-sharp" /></template>
<style>
.eiufiabtg {
  cx: 6px;
  cy: 6.75px;
  r: 1.75px;
}

.h8r22mm8a {
  cx: 18px;
  cy: 6.75px;
  r: 1.75px;
}

.vlqa4vrkv {
  d: path("M12 2.75c1.25 1.4 1.9 2.4 1.9 3.25a1.9 1.9 0 0 1-3.8 0c0-.85.65-1.85 1.9-3.25Z");
}

.wat16xbbe {
  d: path("M12 8.65V12M7.2 8.3L9.5 12m7.3-3.7L14.5 12m-8.25.75h11.5v8.5H6.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
