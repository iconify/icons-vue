<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="z_tl75bou"/><path class="evd4foyzs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:arcade-button" /></template>
<style>
.evd4foyzs {
  d: path("M6.25 13.5v-3.25a5.75 2.75 0 0 1 11.5 0v3.25ZM12 2.75v2m-5.25-1l1 1.5m9.5-1.5l-1 1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z_tl75bou {
  width: 17.5px;
  height: 7.25px;
  x: 3.25px;
  y: 13.5px;
  rx: 2px;
}

</style>
