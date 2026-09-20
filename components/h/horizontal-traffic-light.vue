<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="o5b-dsc0e"/><path class="tin7kabea"/><path class="w8jikl5ad"/><circle class="le6cszbxf"/><circle class="lfbm_jrfj"/><circle class="h5b873cns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:horizontal-traffic-light" /></template>
<style>
.h5b873cns {
  cx: 26.55px;
  cy: 50.44px;
  r: 14.34px;
  fill: var(--svg-color--e43f11, #e43f11);
}

.le6cszbxf {
  cx: 97.11px;
  cy: 50.44px;
  r: 14.34px;
  fill: var(--svg-color--4caf50, #4caf50);
}

.lfbm_jrfj {
  cx: 61.83px;
  cy: 50.44px;
  r: 14.34px;
  fill: var(--svg-color--fcc21b, #fcc21b);
}

.o5b-dsc0e {
  fill: var(--svg-color--616161, #616161);
  d: path("M42.89 126h-7.66a6.3 6.3 0 0 1-6.3-6.3V14.28a6.3 6.3 0 0 1 6.3-6.3h7.66a6.3 6.3 0 0 1 6.3 6.3V119.7a6.3 6.3 0 0 1-6.3 6.3");
}

.tin7kabea {
  fill: var(--svg-color--757576, #757576);
  d: path("M100.84 81.41H32.63c-14.39 0-26.06-11.67-26.06-26.06s11.67-26.06 26.06-26.06h68.21c14.39 0 26.06 11.67 26.06 26.06s-11.67 26.06-26.06 26.06");
}

.w8jikl5ad {
  fill: var(--svg-color--edece4, #edece4);
  d: path("M95.94 76.51H27.72c-14.39 0-26.06-11.67-26.06-26.06s11.67-26.06 26.06-26.06h68.21c14.39 0 26.06 11.67 26.06 26.06c.01 14.39-11.66 26.06-26.05 26.06");
}

</style>
