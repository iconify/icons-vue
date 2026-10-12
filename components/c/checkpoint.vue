<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yclbh-bpn"/><path class="hig6_8bst"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:checkpoint" /></template>
<style>
.hig6_8bst {
  d: path("M9.5 8.5L11 10l3-3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yclbh-bpn {
  d: path("M6 21.25V3M3.25 21.25h5.5M6 4h12.25a1 1 0 0 1 .8 1.6L17 8.5l2.05 2.9a1 1 0 0 1-.8 1.6H6Z");
}

</style>
