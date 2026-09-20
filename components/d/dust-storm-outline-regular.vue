<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="timme522h"/><path class="idl7fxbhb"/><path class="vzfmp7bra"/><path class="ipwz79qoh"/><path class="j3lsn4bia"/><path class="dc0xg9bgf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dust-storm-outline-regular" /></template>
<style>
.dc0xg9bgf {
  d: path("M9 20a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.idl7fxbhb {
  d: path("m17 6 3 -3");
}

.ipwz79qoh {
  d: path("m19 11 3 -3");
}

.j3lsn4bia {
  d: path("M3 16h12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.timme522h {
  d: path("M3 6h14");
}

.vzfmp7bra {
  d: path("M5 11h14");
}

</style>
