<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w_snsacfd"/><path class="kamdbib6v"/><path class="ohhz_s35v"/><path class="h0kd0u5pn"/><path class="xslfg2evh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:late-arriving-data-outline-thin" /></template>
<style>
.h0kd0u5pn {
  d: path("m8 14 4 4 4 -4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kamdbib6v {
  d: path("M2 7h20");
}

.ohhz_s35v {
  d: path("M12 12v6");
}

.w_snsacfd {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.xslfg2evh {
  d: path("M6 21h12");
}

</style>
