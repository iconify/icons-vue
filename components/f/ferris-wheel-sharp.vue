<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="j2auxujcv"/><path class="fnqdxbb0f"/><circle class="leayzzghm"/><path class="l0wii60de"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ferris-wheel-sharp" /></template>
<style>
.fnqdxbb0f {
  d: path("M12 3.5V8m0 4.5V17m-6.75-6.75h4.5m4.5 0h4.5M7.25 5.5l3.1 3.1m3.3 3.3l3.1 3.1m0-9.5l-3.1 3.1m-3.3 3.3L7.25 15");
}

.j2auxujcv {
  cx: 12px;
  cy: 10.25px;
  r: 7.5px;
}

.l0wii60de {
  d: path("m9.25 17.25l-2 4m7.5-4l2 4M5 21.25h14");
}

.leayzzghm {
  cx: 12px;
  cy: 10.25px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
