<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z0s4ddcok"/><path class="eyxfr864l"/><path class="xao2ebc6f"/><path class="tb3edh0qa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:chevron-last-duotone-regular" /></template>
<style>
.eyxfr864l {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m5 5 7 7 -7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tb3edh0qa {
  d: path("m5 5 7 7 -7 7");
}

.xao2ebc6f {
  d: path("M21 5v14");
}

.z0s4ddcok {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
