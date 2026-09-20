<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="p4stwdjmu"/><path class="sok49cc0b"/><path class="hcn7bdzwu"/><path class="v9il_wb-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:histogram-quantile-outline-thin" /></template>
<style>
.hcn7bdzwu {
  d: path("M15 11v7");
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

.p4stwdjmu {
  d: path("M7 13v5");
}

.r3faxubne {
  d: path("M4 4v16");
}

.sok49cc0b {
  d: path("M11 8v10");
}

.v9il_wb-q {
  d: path("M6 10h12");
}

</style>
