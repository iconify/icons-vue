<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bicgcfb5m"/><circle class="jhn2ch9ax"/><circle class="ifs-v5bqs"/><path class="l517yxbln"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dj-controller-sharp" /></template>
<style>
.bicgcfb5m {
  d: path("M2.75 5.75h18.5v12.5H2.75z");
}

.ifs-v5bqs {
  cx: 17px;
  cy: 12px;
  r: 2px;
}

.jhn2ch9ax {
  cx: 7px;
  cy: 12px;
  r: 2px;
}

.l517yxbln {
  d: path("M12 9v6");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
