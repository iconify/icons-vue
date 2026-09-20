<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mjmmdiava"/><path class="v22s1vbap"/><path class="i0gx68gak"/><path class="faidsgbop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chip-add-outline-bold" /></template>
<style>
.faidsgbop {
  d: path("M16 10v4");
}

.i0gx68gak {
  d: path("M14 12h4");
}

.mjmmdiava {
  d: path("M3 12a4 4 0 0 1 4 -4h10a4 4 0 0 1 4 4 4 4 0 0 1 -4 4H7a4 4 0 0 1 -4 -4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v22s1vbap {
  d: path("M6.5 12H11");
}

</style>
