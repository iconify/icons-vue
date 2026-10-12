<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="swodyng-r"/><rect class="hrk9lpb5f"/><path class="er19h6phy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ganjifa-cards" /></template>
<style>
.er19h6phy {
  d: path("m15.5 11.5l2.5 3.13l-2.5 3.12l-2.5-3.12Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hrk9lpb5f {
  width: 11px;
  height: 13.25px;
  x: 10px;
  y: 8px;
  rx: 2px;
}

.swodyng-r {
  d: path("M7 16H5a2 2 0 0 1-2-2V4.75a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2V5");
}

</style>
