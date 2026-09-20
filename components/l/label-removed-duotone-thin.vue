<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fbde_z08y"/><path class="w3hyiobto"/><path class="iq8tuac7e"/><path class="wo_mlccql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:label-removed-duotone-thin" /></template>
<style>
.fbde_z08y {
  fill: currentColor;
  d: path("M3 6h10l8 8 -8 8H3Z");
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

.iq8tuac7e {
  d: path("m10 11.5 4 4");
}

.w3hyiobto {
  d: path("M3 6h10l8 8 -8 8H3Z");
}

.wo_mlccql {
  d: path("m14 11.5 -4 4");
}

</style>
