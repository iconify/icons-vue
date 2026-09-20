<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dthqm4bkd"/><path class="zt9xgrbcr"/><path class="uvgrx_yvv"/><path class="tdul-wdwn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:deploy-duotone-thin" /></template>
<style>
.dthqm4bkd {
  fill: currentColor;
  d: path("M13.5 11H17a3 3 0 0 1 3 3v3a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3v-3a3 3 0 0 1 3 -3h3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tdul-wdwn {
  d: path("m9 6 3 -3 3 3");
}

.uvgrx_yvv {
  d: path("M12 3v5");
}

.zt9xgrbcr {
  d: path("M13.5 11H17a3 3 0 0 1 3 3v3a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3v-3a3 3 0 0 1 3 -3h3.5");
}

</style>
