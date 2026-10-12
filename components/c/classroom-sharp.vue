<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qpfcnacts"/><circle class="l-zq-1mft"/><circle class="ejqc9bb9x"/><circle class="a870vdb4y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:classroom-sharp" /></template>
<style>
.a870vdb4y {
  cx: 18.75px;
  cy: 18.25px;
  r: 2px;
}

.ejqc9bb9x {
  cx: 12px;
  cy: 18.25px;
  r: 2px;
}

.l-zq-1mft {
  cx: 5.25px;
  cy: 18.25px;
  r: 2px;
}

.qpfcnacts {
  d: path("M2.75 2.75h18.5v10H2.75zm3.75 5h7");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
