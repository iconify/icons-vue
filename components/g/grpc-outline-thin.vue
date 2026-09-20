<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tc8fh3off"/><path class="lpi5lkbmw"/><path class="bp52f-cpd"/><path class="wr9epib_z"/><path class="r2-193ooz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:grpc-outline-thin" /></template>
<style>
.bp52f-cpd {
  d: path("m11 6 3 3 -3 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lpi5lkbmw {
  d: path("M2 9h12");
}

.r2-193ooz {
  d: path("m5 12 -3 3 3 3");
}

.tc8fh3off {
  d: path("M14 6a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

.wr9epib_z {
  d: path("M2 15h12");
}

</style>
