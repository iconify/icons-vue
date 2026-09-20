<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lyp1l130n"/><path class="njnz25bwe"/><path class="bx3fv3b8c"/><path class="pmuiqo95v"/><path class="vdy_x0b6n"/><path class="oquq7bbql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dressing-table-duotone-thin" /></template>
<style>
.bx3fv3b8c {
  d: path("M12 13v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lyp1l130n {
  fill: currentColor;
  d: path("M8 8a4 5 0 1 1 8 0 4 5 0 1 1 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.njnz25bwe {
  d: path("M8 8a4 5 0 1 1 8 0 4 5 0 1 1 -8 0");
}

.oquq7bbql {
  d: path("M20 17v4");
}

.pmuiqo95v {
  d: path("M2 17h20");
}

.vdy_x0b6n {
  d: path("M4 17v4");
}

</style>
