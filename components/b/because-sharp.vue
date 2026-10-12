<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="vha_j0t2o"/><circle class="aewuuhb3v"/><circle class="qg0ecjuof"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:because-sharp" /></template>
<style>
.aewuuhb3v {
  cx: 18.5px;
  cy: 6.25px;
  r: 2.5px;
}

.qg0ecjuof {
  cx: 12px;
  cy: 18px;
  r: 2.5px;
}

.vha_j0t2o {
  cx: 5.5px;
  cy: 6.25px;
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
