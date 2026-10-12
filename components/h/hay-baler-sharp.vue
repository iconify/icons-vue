<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bwxegxb5h"/><path class="lhll1pu2b"/><circle class="r19_o2kzq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hay-baler-sharp" /></template>
<style>
.bwxegxb5h {
  d: path("m8.53 9.97l2.44-2.44l.53-.53h9.75v10.75l-.53.53l-2.44 2.44l-.53.53H8V10.5z");
}

.lhll1pu2b {
  d: path("M8 10.5h9.75l3.5-3.5m-3.5 3.5v10.75m-6.5-10.75v10.75M14.5 10.5v10.75M8 16H5.75");
}

.r19_o2kzq {
  cx: 4.25px;
  cy: 16px;
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
