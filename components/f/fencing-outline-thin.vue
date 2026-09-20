<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ywch90sba"/><path class="uwi1_aczt"/><path class="u1gt5absq"/><path class="r0uia_bgu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fencing-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r0uia_bgu {
  d: path("M19 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.u1gt5absq {
  d: path("M3 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.uwi1_aczt {
  d: path("M21 4 5 20");
}

.ywch90sba {
  d: path("m3 4 16 16");
}

</style>
