<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dh-xp411l"/><path class="dz0mer_8h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ground-truth" /></template>
<style>
.dh-xp411l {
  cx: 12px;
  cy: 9.5px;
  r: 6.75px;
}

.dz0mer_8h {
  d: path("m9 9.75l2 2l4-4m-3 8.5v4.5m-7.75 0h15.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
