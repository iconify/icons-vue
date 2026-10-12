<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="vnljrxsbd"/><path class="crdme_b_t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:accelerator-pedal" /></template>
<style>
.crdme_b_t {
  d: path("M5.5 21.25h13M12 18.5v2.75m-1.75-8.75L12 7.75l1.75 4.75m-3-1.5h2.5m-3 4.25h3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vnljrxsbd {
  width: 8px;
  height: 15.75px;
  x: 8px;
  y: 2.75px;
  rx: 2.5px;
}

</style>
