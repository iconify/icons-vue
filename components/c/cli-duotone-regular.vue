<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="em7uy10sd"/><path class="zt7ewvbex"/><path class="h_ozghejt"/><path class="j4cr2gb0p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:cli-duotone-regular" /></template>
<style>
.em7uy10sd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m4 7 5 5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h_ozghejt {
  d: path("m4 7 5 5 -5 5");
}

.j4cr2gb0p {
  d: path("M11 17h9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zt7ewvbex {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 17h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
