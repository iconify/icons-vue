<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vvnssjb-o"/><path class="i7kaf-qlz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:health-check-duotone-bold" /></template>
<style>
.i7kaf-qlz {
  d: path("M3 12h5V6h4v12h4v-6h5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vvnssjb-o {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h5V6h4v12h4v-6h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
