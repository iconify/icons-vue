<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j6br2vbzt"/><path class="dmzb83bqo"/><path class="xmuq15b2m"/><path class="oeegk46dw"/><path class="kdt_obwbe"/><path class="zf7mx_7mn"/><path class="ufignx6hm"/><path class="cy34vrbps"/><path class="ooykrqbbx"/><path class="t3p_xpene"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bucket-data-duotone-regular" /></template>
<style>
.cy34vrbps {
  d: path("M10 8.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.dmzb83bqo {
  fill: currentColor;
  d: path("M15.5 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.j6br2vbzt {
  fill: currentColor;
  d: path("M4.5 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.kdt_obwbe {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 13v7h7v-7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oeegk46dw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 13v7h7v-7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ooykrqbbx {
  d: path("M3 13v7h7v-7");
}

.t3p_xpene {
  d: path("M14 13v7h7v-7");
}

.ufignx6hm {
  d: path("M15.5 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.xmuq15b2m {
  fill: currentColor;
  d: path("M10 8.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zf7mx_7mn {
  d: path("M4.5 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
