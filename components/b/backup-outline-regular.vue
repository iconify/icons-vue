<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uigc87b2x"/><path class="miyi8eb4c"/><path class="vhf3_kexp"/><path class="vy337188j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:backup-outline-regular" /></template>
<style>
.miyi8eb4c {
  d: path("M4 5a8 3 0 0 0 16 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uigc87b2x {
  d: path("M4 5a8 3 0 0 1 16 0v5a8 3 0 0 1 -16 0Z");
}

.vhf3_kexp {
  d: path("M12 16v5");
}

.vy337188j {
  d: path("m9 18 3 3 3 -3");
}

</style>
