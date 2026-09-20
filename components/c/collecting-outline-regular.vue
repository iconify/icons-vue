<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cnjkjfbvs"/><path class="wew0vnk_n"/><path class="n2gldhbms"/><path class="phma5vbaw"/><path class="kc9g0xbtf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:collecting-outline-regular" /></template>
<style>
.cnjkjfbvs {
  d: path("M3 5v14h18V5Z");
}

.kc9g0xbtf {
  d: path("M5.5 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.n2gldhbms {
  d: path("M5.5 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.phma5vbaw {
  d: path("M14.5 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.wew0vnk_n {
  d: path("M12 5v14");
}

</style>
