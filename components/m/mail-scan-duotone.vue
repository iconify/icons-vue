<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xh_a97bcg"/><path class="ca29gjbwp"/><path class="d6fm1lbsa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-scan-duotone" /></template>
<style>
.ca29gjbwp {
  d: path("M3 6L11.36361 8.84948C11.74386 9.05015 12.25614 9.05015 12.63639 8.84948L21 6M2 13H22");
}

.d6fm1lbsa {
  stroke-opacity: 0.4;
  d: path("M3 17H10M21 17H14M20 21H18M14 21H10M6 21H4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xh_a97bcg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 14H3C2.4477 14 2 13.5523 2 13V6C2 3.7909 3.7909 2 6 2H18C20.2091 2 22 3.7909 22 6V13C22 13.5523 21.5523 14 21 14Z");
  stroke: none;
}

</style>
