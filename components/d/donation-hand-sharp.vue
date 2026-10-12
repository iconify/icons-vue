<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="uselc-4uc"/><circle class="jrxp_-qgm"/><path class="e094-yb0n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:donation-hand-sharp" /></template>
<style>
.e094-yb0n {
  d: path("M12 5.25v3");
}

.jrxp_-qgm {
  cx: 12px;
  cy: 6.75px;
  r: 3.75px;
}

.uselc-4uc {
  d: path("M2.75 11.5h3.5l1 3.5c.5 1.5 2.25 2.5 4.75 2.5s4.25-1 4.75-2.5l1-3.5h3.5l-2 5.5c-1 3-4 4.25-7.25 4.25S5.75 20 4.75 17Zm9.25 6v3.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
