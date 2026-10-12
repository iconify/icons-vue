<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="u0o7738tc"/><path class="gx687bb4n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:charger" /></template>
<style>
.gx687bb4n {
  d: path("M9.5 2.75v4.5m5-4.5v4.5m-2.5 9.5v4.5m.75-11.75l-2 2.75h2.5l-2 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u0o7738tc {
  width: 12.5px;
  height: 9.5px;
  x: 5.75px;
  y: 7.25px;
  rx: 2.5px;
}

</style>
