<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="rjtw7lbeb"/><path class="qx6h-1u4w"/><path class="q_boe0brz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:face-id-sharp" /></template>
<style>
.q_boe0brz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9.5v3.25h-.75m-2 2.5L12 17.57l2.75-2.32");
}

.qx6h-1u4w {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 9.75h.01m5.99 0h.01");
}

.rjtw7lbeb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 8V3.75H8m8 0h4.25V8m0 8v4.25H16m-8 0H3.75V16");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
