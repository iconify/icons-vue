<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y4_6s7b5v"/><path class="wuvisubmw"/><path class="zvb1nubon"/><path class="e36i9zwxh"/><path class="wvvllx1oh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:encyclopedia-outline-regular" /></template>
<style>
.e36i9zwxh {
  d: path("M11 15h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wuvisubmw {
  d: path("M8 3v18");
}

.wvvllx1oh {
  d: path("M11 18h6");
}

.y4_6s7b5v {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.zvb1nubon {
  d: path("M11 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
