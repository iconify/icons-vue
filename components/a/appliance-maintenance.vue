<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qvzeih-fx"/><path class="ix9htdcxp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:appliance-maintenance" /></template>
<style>
.ix9htdcxp {
  d: path("M13.9 15.5H6V11h8.5v2.9m4.75.35a2.5 2.5 0 1 1-2.5 2.5m.75 1.75L15 21");
}

.qvzeih-fx {
  d: path("M13.1 19H2.5V2.5H18v8.9M2.5 7.5H18M6 5h.01M9.5 5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
