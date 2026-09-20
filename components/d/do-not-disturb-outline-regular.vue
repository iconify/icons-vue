<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qmakhcstn"/><path class="rgjkvwbqj"/><path class="at7ws5bbl"/><path class="js578gb4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:do-not-disturb-outline-regular" /></template>
<style>
.at7ws5bbl {
  d: path("M9.5 12h5");
}

.js578gb4i {
  d: path("M9.5 16h5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qmakhcstn {
  d: path("M9.5 3a2.5 2.5 0 0 1 5 0v2.5a2.5 2.5 0 0 1 -5 0Z");
}

.rgjkvwbqj {
  d: path("M7 8h10v13H7Z");
}

</style>
