<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pwi6umbbd"/><circle class="zwd9fjbht"/><circle class="nbxv73-5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kick-scooter-sharp" /></template>
<style>
.nbxv73-5j {
  cx: 18.75px;
  cy: 18.5px;
  r: 2.25px;
}

.pwi6umbbd {
  d: path("M3.25 16.25h15m.08.04L16 4m-2.25 0h4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zwd9fjbht {
  cx: 5.25px;
  cy: 18.5px;
  r: 2.25px;
}

</style>
