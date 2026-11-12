<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fg37-14pa"/><path class="beu8enohc"/><path class="oqpf2r_po"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:frame-line-duotone" /></template>
<style>
.beu8enohc {
  d: path("M22 19H2");
}

.fg37-14pa {
  d: path("M22 5H19M19 5H2M19 5V22M19 5V2");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oqpf2r_po {
  d: path("M5 22L5 2");
}

</style>
