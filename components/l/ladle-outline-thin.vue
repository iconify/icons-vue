<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mvm7r4bea"/><path class="jinvu3zma"/><path class="uac-t6brn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ladle-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jinvu3zma {
  d: path("M16 14a4 4 0 0 1 -8 0");
}

.mvm7r4bea {
  d: path("M8 14h8");
}

.uac-t6brn {
  d: path("M16 14c1 -5 -1 -10 -4 -11");
}

</style>
