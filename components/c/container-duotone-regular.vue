<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tgl1-bcis"/><path class="xxsav7b5u"/><path class="vavi9cbgb"/><path class="x5li7lwaz"/><path class="bppr_wbcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:container-duotone-regular" /></template>
<style>
.bppr_wbcq {
  d: path("M16 7v12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tgl1-bcis {
  fill: currentColor;
  d: path("M3 9a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vavi9cbgb {
  d: path("M8 7v12");
}

.x5li7lwaz {
  d: path("M12 7v12");
}

.xxsav7b5u {
  d: path("M3 9a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
