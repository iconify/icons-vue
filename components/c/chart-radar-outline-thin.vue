<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kj_xiu02e"/><path class="zwbbmtbru"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-radar-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kj_xiu02e {
  d: path("m12 4 8 8 -8 8 -8 -8Z");
}

.zwbbmtbru {
  d: path("m12 8 4 4 -4 4 -4 -4Z");
}

</style>
