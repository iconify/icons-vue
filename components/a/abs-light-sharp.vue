<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><path class="h-1q50eiy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:abs-light-sharp" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.h-1q50eiy {
  d: path("m5.5 14.5l1.75-5l1.75 5m-2.85-1.75h2.2m2.4 1.75v-5h2.5V12h-2.5h2.75v2.5h-1.25ZM18 10l-.5-.5h-2.05v1.1c0 1.4 2.75.9 2.75 2.35v1.1h-2.275l-.525-.6");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
