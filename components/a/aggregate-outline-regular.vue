<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s9xdwbcyw"/><path class="pesxdybze"/><path class="nkayykbew"/><path class="b603-acaz"/><path class="adiugjbhs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:aggregate-outline-regular" /></template>
<style>
.adiugjbhs {
  d: path("m15 9 3 3 -3 3");
}

.b603-acaz {
  d: path("M10 12h8");
}

.nkayykbew {
  d: path("m3 19 7 -7");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pesxdybze {
  d: path("M3 12h7");
}

.s9xdwbcyw {
  d: path("m3 5 7 7");
}

</style>
