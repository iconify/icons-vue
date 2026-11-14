<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pkx-yubrt"/><path class="f5eyxvb5b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cover-slip" /></template>
<style>
.f5eyxvb5b {
  d: path("m10.115 12.923l1.25-3A1.5 1.5 0 0 1 12.75 9H15a1.5 1.5 0 0 1 1.385 2.077l-1.25 3A1.5 1.5 0 0 1 13.75 15H11.5a1.5 1.5 0 0 1-1.385-2.077");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pkx-yubrt {
  d: path("m3.51 15.577l3.541-8.5A1.75 1.75 0 0 1 8.667 6h10.208a1.75 1.75 0 0 1 1.615 2.423l-3.541 8.5A1.75 1.75 0 0 1 15.333 18H5.125a1.75 1.75 0 0 1-1.615-2.423");
}

</style>
