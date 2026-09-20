<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pc9haabcx"/><path class="erreycbys"/><path class="syzpzeigb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cadence-outline-regular" /></template>
<style>
.erreycbys {
  d: path("m12 13 5 -5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pc9haabcx {
  d: path("M5 13a7 7 0 1 0 14 0 7 7 0 1 0 -14 0");
}

.syzpzeigb {
  d: path("m15 4 5 5");
}

</style>
