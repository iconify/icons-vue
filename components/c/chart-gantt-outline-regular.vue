<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="r_r678bum"/><path class="lqiw_3bos"/><path class="xyhj-ubbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chart-gantt-outline-regular" /></template>
<style>
.lqiw_3bos {
  d: path("M10 12h7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.r_r678bum {
  d: path("M6 7h6");
}

.r3faxubne {
  d: path("M4 4v16");
}

.xyhj-ubbr {
  d: path("M13 17h7");
}

</style>
