<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="kx10lybnk"/><circle class="nm_s7seyo"/><circle class="ags78j8uq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ellipsis-sign" /></template>
<style>
.ags78j8uq {
  cx: 19px;
  cy: 17.5px;
  r: 1.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kx10lybnk {
  cx: 5px;
  cy: 17.5px;
  r: 1.75px;
}

.nm_s7seyo {
  cx: 12px;
  cy: 17.5px;
  r: 1.75px;
}

</style>
