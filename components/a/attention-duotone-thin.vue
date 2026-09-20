<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wfyw8dbnu"/><path class="g0r36obgd"/><path class="w4mlg7f2w"/><path class="cajt03bfr"/><path class="wsohn5btf"/><path class="enrpg0aoq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:attention-duotone-thin" /></template>
<style>
.cajt03bfr {
  d: path("m4 20 5 -5");
}

.enrpg0aoq {
  d: path("M9 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.g0r36obgd {
  d: path("m4 4 5 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w4mlg7f2w {
  d: path("m20 4 -5 5");
}

.wfyw8dbnu {
  fill: currentColor;
  d: path("M9 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wsohn5btf {
  d: path("m20 20 -5 -5");
}

</style>
