<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="z-_gsncpq"/><circle class="vtw09psrf"/><path class="cmozqx4uq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chandelier-sharp" /></template>
<style>
.cmozqx4uq {
  d: path("M12 17.75v2.5M4.75 11V8.75M19.25 11V8.75M8.5 14.25V11.5m7 2.75V11.5M4.75 4L6 5.167V6a1.25 1.25 0 0 1-2.5 0v-.833zm14.5 0l1.25 1.167V6A1.25 1.25 0 0 1 18 6v-.833zM8.5 6.75l1.25 1.167v.833a1.25 1.25 0 0 1-2.5 0v-.833zm7 0l1.25 1.167v.833a1.25 1.25 0 0 1-2.5 0v-.833z");
}

.vtw09psrf {
  cx: 12px;
  cy: 16.25px;
  r: 1.5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z-_gsncpq {
  d: path("M10 2.75h4m-2 0v12M4.75 11c0 2.5 3 3.75 7.25 3.75s7.25-1.25 7.25-3.75m-16 0h3m11.5 0h3");
}

</style>
