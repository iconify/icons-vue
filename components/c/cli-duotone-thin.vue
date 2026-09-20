<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z3ui8tboa"/><path class="rgv-h7b7q"/><path class="h_ozghejt"/><path class="j4cr2gb0p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cli-duotone-thin" /></template>
<style>
.h_ozghejt {
  d: path("m4 7 5 5 -5 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j4cr2gb0p {
  d: path("M11 17h9");
}

.rgv-h7b7q {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 17h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z3ui8tboa {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 7 5 5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
