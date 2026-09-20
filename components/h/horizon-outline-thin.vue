<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zugrvnb7t"/><path class="t-oxscctn"/><path class="j08f9ezai"/><path class="dihddo_by"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:horizon-outline-thin" /></template>
<style>
.dihddo_by {
  d: path("M6 18h12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j08f9ezai {
  d: path("m12 13 4 -4 4 4");
}

.t-oxscctn {
  d: path("m5 13 4 -4 4 4");
}

.zugrvnb7t {
  d: path("M2 13h20");
}

</style>
