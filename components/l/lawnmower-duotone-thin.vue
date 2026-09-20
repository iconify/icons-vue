<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uxzcf0wqi"/><path class="fti-unbge"/><path class="iackuoo5o"/><path class="q737qqeus"/><path class="hkrm8eiuq"/><path class="aq5i5tblx"/><path class="l4egjkszt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:lawnmower-duotone-thin" /></template>
<style>
.aq5i5tblx {
  d: path("M4 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.fti-unbge {
  fill: currentColor;
  d: path("M4 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hkrm8eiuq {
  d: path("m16 13 5 -5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iackuoo5o {
  fill: currentColor;
  d: path("M12 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.l4egjkszt {
  d: path("M12 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.q737qqeus {
  d: path("M4 11v4h12v-4Z");
}

.uxzcf0wqi {
  fill: currentColor;
  d: path("M4 11v4h12v-4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
