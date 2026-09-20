<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wmtj7ubjb"/><path class="bw1nw8b2t"/><path class="rrzohjbez"/><path class="n3ywj3bst"/><path class="s5rw9kvzr"/><path class="ltl8_ccdr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:day-low-outline-regular" /></template>
<style>
.bw1nw8b2t {
  d: path("M10 17.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ltl8_ccdr {
  d: path("M3 6h3");
}

.n3ywj3bst {
  d: path("M19 7v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rrzohjbez {
  d: path("M12 12v3");
}

.s5rw9kvzr {
  d: path("M16.5 10.5 19 13l2.5 -2.5");
}

.wmtj7ubjb {
  d: path("M9.5 15V6a2.5 2.5 0 0 1 5 0v9a4.5 4.5 0 1 1 -5 0");
}

</style>
