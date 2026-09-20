<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="atoje4bsc"/><path class="e2r0vmbrh"/><path class="kpiqhd6nn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:basement-outline-thin" /></template>
<style>
.atoje4bsc {
  d: path("M2 6h20");
}

.e2r0vmbrh {
  d: path("M4 6v5h5v4h5v4h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kpiqhd6nn {
  d: path("M20 18.5V21");
}

</style>
