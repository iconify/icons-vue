<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="t0jrdmbrp"/><path class="kjimvnuvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:checkbox" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kjimvnuvm {
  d: path("M8 12.25L10.75 15L16 9.5");
}

.t0jrdmbrp {
  width: 17.5px;
  height: 17.5px;
  x: 3.25px;
  y: 3.25px;
  rx: 4px;
}

</style>
