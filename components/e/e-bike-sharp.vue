<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fs808ib-k"/><circle class="testxab1c"/><circle class="qispqfbwt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:e-bike-sharp" /></template>
<style>
.fs808ib-k {
  d: path("M7.75 17.75h3L8.46 8M7 8h3m.75 9.75l2.96-5.21m1.48-2.61L16 8.5l2.04 6.85M16 8.5l-.82-2.75h-1.75m.53 6.36l.98-1.75l.25-.43l-.44-.25l-.64-.36l-.44-.25l-.25.43l-.98 1.75l-.25.43l.44.25l.64.36l.44.25z");
}

.qispqfbwt {
  cx: 18.75px;
  cy: 17.75px;
  r: 2.5px;
}

.testxab1c {
  cx: 5.25px;
  cy: 17.75px;
  r: 2.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
