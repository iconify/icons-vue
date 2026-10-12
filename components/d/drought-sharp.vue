<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="vxcqd5b0h"/><path class="vmw-ke_8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:drought-sharp" /></template>
<style>
.vmw-ke_8r {
  d: path("M7.25 9H6m2.64-3.36l-.88-.88M12 4.25V3m3.36 2.64l.88-.88M16.75 9H18M2.75 15.25h18.5m-8.75 0l-1.5 2L12.75 19l-1 2.25");
}

.vxcqd5b0h {
  cx: 12px;
  cy: 9px;
  r: 2.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
