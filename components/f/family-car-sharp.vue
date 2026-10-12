<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="e1wnqxbnl"/><circle class="rqad3rgfm"/><circle class="ay165rc5y"/><path class="mpb8zwbqv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:family-car-sharp" /></template>
<style>
.ay165rc5y {
  cx: 17px;
  cy: 19.25px;
  r: 1.75px;
}

.e1wnqxbnl {
  d: path("M2.75 14v-2.6l-.001-1.592L4.3 9.45l2.45-.55L8.8 5.45l.592-.96l1.128.01h2.96l1.128-.01l.592.96l2.05 3.45l2.45.55l1.551.358l-.001 1.592V15H2.75z");
}

.mpb8zwbqv {
  d: path("m12 12.75l-1.6-1.55A1.05 1.05 0 0 1 12 9.85a1.05 1.05 0 0 1 1.6 1.35Z");
}

.rqad3rgfm {
  cx: 7px;
  cy: 19.25px;
  r: 1.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
