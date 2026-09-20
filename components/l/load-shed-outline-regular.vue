<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u4z3yfbwn"/><path class="kpspt_bpo"/><path class="sd8rzobni"/><path class="bcvts4b4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:load-shed-outline-regular" /></template>
<style>
.bcvts4b4i {
  d: path("M13 18.5V21");
}

.kpspt_bpo {
  d: path("M7 8h10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sd8rzobni {
  d: path("M17 17v2.5");
}

.u4z3yfbwn {
  d: path("M4 5v9h16V5");
}

</style>
