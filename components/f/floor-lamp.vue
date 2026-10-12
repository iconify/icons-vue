<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aetny_bbi"/><path class="xma48ubfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:floor-lamp" /></template>
<style>
.aetny_bbi {
  d: path("M7.5 20.75V8.5a4.75 4.75 0 0 1 9.5 0V9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xma48ubfn {
  d: path("M13.5 12.5a3.5 3.5 0 0 1 7 0ZM4.75 21h5.5");
}

</style>
