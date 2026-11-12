<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eoe13w36s"/><path class="bjr4uf7pk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-left-to-line-broken" /></template>
<style>
.bjr4uf7pk {
  d: path("M3 4L3 8M3 12L3 20");
}

.eoe13w36s {
  d: path("M21 12L8 12M12.375 16L8 12L12.375 8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
