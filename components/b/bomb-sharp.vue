<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="og1g0-edb"/><path class="uukk86bow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bomb-sharp" /></template>
<style>
.og1g0-edb {
  cx: 10.5px;
  cy: 14px;
  r: 7.25px;
}

.uukk86bow {
  d: path("m6.75 13.25l.471-2.529l2.529-.471m5.88-1.38l1.208-1.208l-.308-1.542M19 2.75l.18 1.32l1.32.18l-1.32.18L19 5.75l-.18-1.32l-1.32-.18l1.32-.18z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
