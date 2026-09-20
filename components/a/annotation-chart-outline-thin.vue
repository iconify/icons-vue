<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="hbw5_ccle"/><path class="ze3hawb4v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:annotation-chart-outline-thin" /></template>
<style>
.hbw5_ccle {
  d: path("m7 17 4 -4 4 4 4 -4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r3faxubne {
  d: path("M4 4v16");
}

.ze3hawb4v {
  d: path("M14 6v12");
}

</style>
