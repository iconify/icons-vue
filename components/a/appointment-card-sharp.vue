<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hmz588b6d"/><circle class="yitct_buo"/><path class="lmoc36boq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:appointment-card-sharp" /></template>
<style>
.hmz588b6d {
  d: path("M2.75 5.25h18.5v13.5H2.75z");
}

.lmoc36boq {
  d: path("M8 10.5V12h1.25M13 9.75h5m-5 2.5h5m-5 2.5h3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yitct_buo {
  cx: 8px;
  cy: 12px;
  r: 3px;
}

</style>
