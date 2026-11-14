<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qo6s1mbjv"/><path class="j7_phoows"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dentist" /></template>
<style>
.j7_phoows {
  d: path("M9 6a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM4 21.5c0-2 3.5-3.25 8-3.25s8 1.25 8 3.25M12 6h.01");
}

.qo6s1mbjv {
  d: path("M9 6H7v4.5a5 5 0 0 0 10 0V6h-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
