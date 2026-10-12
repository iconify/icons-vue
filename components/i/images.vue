<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ygdbjfurc"/><path class="wnk968b4u"/><circle class="riv17abjk"/><path class="ubjnbdc4n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:images" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.riv17abjk {
  cx: 7.75px;
  cy: 11.25px;
  r: 1.5px;
}

.ubjnbdc4n {
  d: path("m2.75 18.5l4-4a1.6 1.6 0 0 1 2.25 0l4.25 4.25M12 17.5l1.6-1.6a1.6 1.6 0 0 1 2.25 0l2.4 2.4");
}

.wnk968b4u {
  d: path("M6.75 3.75h12a2.5 2.5 0 0 1 2.5 2.5v11");
}

.ygdbjfurc {
  width: 15.5px;
  height: 14.5px;
  x: 2.75px;
  y: 6.75px;
  rx: 2.5px;
}

</style>
