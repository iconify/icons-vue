<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bxwb8qsga"/><path class="mep_pif7d"/><path class="q84iiacic"/><path class="a-w-mldxi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:caravan-outline-thin" /></template>
<style>
.a-w-mldxi {
  d: path("M19 10h3");
}

.bxwb8qsga {
  d: path("M3 15V5h16v10Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mep_pif7d {
  d: path("M6 8h5v4H6Z");
}

.q84iiacic {
  d: path("M6 17.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
