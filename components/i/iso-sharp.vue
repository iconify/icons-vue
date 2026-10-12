<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="zo7cudbhk"/><path class="hqpnkrbsc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:iso-sharp" /></template>
<style>
.hqpnkrbsc {
  d: path("M12.25 9.75a1.75 1.5 0 0 0-1.5-.5h-.5a1.4 1.4 0 0 0 0 2.75h.5a1.4 1.4 0 0 1 0 2.75h-.5a1.75 1.5 0 0 1-1.5-.5m9-2.25a1.75 2.75 0 1 1-3.5 0a1.75 2.75 0 1 1 3.5 0");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zo7cudbhk {
  d: path("M2.75 5.25h18.5v13.5H2.75zm3.5 4v5.5");
}

</style>
