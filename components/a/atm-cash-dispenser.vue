<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d7cq2obst"/><path class="qy9nkbc4u"/><path class="x92ih53bh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:atm-cash-dispenser" /></template>
<style>
.d7cq2obst {
  d: path("M4 2h16v13.5H4Z");
}

.qy9nkbc4u {
  d: path("M7 4.75h10v5H7Zm1.5 8h.01m3.49 0h.01m3.49 0h.01M6.5 15.5v5a1 1 0 0 0 1 1h9a1 1 0 0 0 1-1v-5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x92ih53bh {
  d: path("M9.75 18.5a2.25 1.25 0 1 0 4.5 0a2.25 1.25 0 1 0-4.5 0Z");
}

</style>
