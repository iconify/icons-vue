<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vkp-1wbef"/><path class="svay_hbrn"/><path class="rw4xuxb2g"/><path class="vn6-di86m"/><path class="cfeplwbzd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:compost-bin-duotone-thin" /></template>
<style>
.cfeplwbzd {
  d: path("M12 17c-3 0 -4 -2 -4 -4 3 0 4 2 4 4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rw4xuxb2g {
  d: path("M6 10v10h12V10Z");
}

.svay_hbrn {
  fill: currentColor;
  d: path("M12 17c-3 0 -4 -2 -4 -4 3 0 4 2 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vkp-1wbef {
  fill: currentColor;
  d: path("M6 10v10h12V10Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vn6-di86m {
  d: path("M4 7h16");
}

</style>
