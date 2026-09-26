<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y5-v_xbay"/><path class="u-7ninbzs"/><path class="dno4_nblm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cast-two-tone" /></template>
<style>
.dno4_nblm {
  fill: currentColor;
  d: path("M3 20C3 20.5523 2.5523 21 2 21C1.4477 21 1 20.5523 1 20C1 19.4477 1.4477 19 2 19C2.5523 19 3 19.4477 3 20Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u-7ninbzs {
  d: path("M2 16C4.2091 16 6 17.7909 6 20M2 12C6.4183 12 10 15.5817 10 20");
}

.y5-v_xbay {
  stroke-opacity: 0.4;
  d: path("M2 8L2 7C2 5.3431 3.3432 4 5 4L19 4C20.6569 4 22 5.3431 22 7L22 17C22 18.6569 20.6569 20 19 20L14 20");
}

</style>
