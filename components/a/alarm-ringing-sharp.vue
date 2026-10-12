<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="x7lqlmblc"/><path class="qxj3vizju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:alarm-ringing-sharp" /></template>
<style>
.qxj3vizju {
  d: path("m4 7.25l3-2.5m13 2.5l-3-2.5m-9.25 14l-1.25 1.5m9.75-1.5l1.25 1.5M2.75 12v3.5m18.5-3.5v3.5M12 10.25v3l1.75 1.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x7lqlmblc {
  cx: 12px;
  cy: 13.25px;
  r: 6.25px;
}

</style>
