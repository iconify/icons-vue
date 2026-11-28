<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rki1bmbri"/><path class="n4uolibjk"/><path clip-rule="evenodd" class="o77a-7b-i"/><path class="d8r3rub5k"/><path clip-rule="evenodd" class="z32lplb3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cast-alert-two-tone" /></template>
<style>
.d8r3rub5k {
  d: path("M19 4V6");
}

.n4uolibjk {
  d: path("M2 16C4.2091 16 6 17.791 6 20M2 12C6.4183 12 10 15.582 10 20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o77a-7b-i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 20C3 20.552 2.5523 21 2 21C1.4477 21 1 20.552 1 20C1 19.448 1.4477 19 2 19C2.5523 19 3 19.448 3 20Z");
  stroke: none;
}

.rki1bmbri {
  stroke-opacity: 0.4;
  d: path("M2 8V7C2 5.343 3.3432 4 5 4H12M22 14V17C22 18.657 20.6569 20 19 20H14");
}

.z32lplb3e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 10C20 10.552 19.5523 11 19 11C18.4477 11 18 10.552 18 10C18 9.448 18.4477 9 19 9C19.5523 9 20 9.448 20 10Z");
  stroke: none;
}

</style>
