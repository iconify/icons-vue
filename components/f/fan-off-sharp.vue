<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dh-xp411l"/><path class="uwpproo4e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fan-off-sharp" /></template>
<style>
.dh-xp411l {
  cx: 12px;
  cy: 9.5px;
  r: 6.75px;
}

.uwpproo4e {
  d: path("m12 9.5l-1.87-3.25l1.875-2.827L13.88 6.25Zm0 0h3.75l1.514 3.034l-3.384.216Zm0 0l-1.87 3.25l-3.4-.202L8.25 9.5Zm0 6.75v5m-4 0h8");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
