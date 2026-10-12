<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="bfv48acnr"/><path class="zrnuaslnh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kite-shape-sharp" /></template>
<style>
.bfv48acnr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.53 3.79l4.69 3.92L19.75 9l-1.05 1.7l-5.65 9.1L12 21.5l-1.05-1.7l-5.65-9.1L4.25 9l1.53-1.29l4.69-3.92L12 2.5z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zrnuaslnh {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 10.5h.01");
}

</style>
