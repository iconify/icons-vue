<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="msk_ilb5g"/><path class="ielxrbcab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fabric-swatch" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ielxrbcab {
  d: path("M9 8.75h12q.25 0 .14.23l-.78 1.62q-.11.23 0 .46l.78 1.63q.11.23 0 .46l-.78 1.62q-.11.23 0 .46l.78 1.62q.11.23 0 .46l-.78 1.63q-.11.23 0 .46l.78 1.62q.11.23-.12.12l-1.62-.78q-.23-.11-.46 0l-1.63.78q-.23.11-.46 0l-1.62-.78q-.23-.11-.46 0l-1.62.78q-.23.11-.46 0l-1.63-.78q-.23-.11-.46 0l-1.62.78q-.23.11-.23-.14V9q0-.25.25-.25");
}

.msk_ilb5g {
  width: 12.5px;
  height: 12.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.5px;
}

</style>
