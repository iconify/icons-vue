<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ymw3aibdo"/><path class="mhnr27bap"/><path class="fx4s06o2o"/><path class="cwioy_h_g"/><path class="nggq41d_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:explain-plan-outline-thin" /></template>
<style>
.cwioy_h_g {
  d: path("M4 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.fx4s06o2o {
  d: path("M6 13v-3h12v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mhnr27bap {
  d: path("M12 7v3");
}

.nggq41d_a {
  d: path("M16 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ymw3aibdo {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
