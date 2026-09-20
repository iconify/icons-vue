<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j-v_opwjt"/><path class="gquwhbknj"/><path class="uokpg3btu"/><path class="slxnpv8ya"/><path class="yngda3bvc"/><path class="r15cr0b9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:autonomy-level-duotone-regular" /></template>
<style>
.gquwhbknj {
  d: path("M6 5v3");
}

.j-v_opwjt {
  fill: currentColor;
  d: path("M10 15a2 2 0 0 1 2 -2 2 2 0 0 1 2 2 2 2 0 0 1 -2 2 2 2 0 0 1 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r15cr0b9g {
  d: path("M10 15a2 2 0 0 1 2 -2 2 2 0 0 1 2 2 2 2 0 0 1 -2 2 2 2 0 0 1 -2 -2");
}

.slxnpv8ya {
  d: path("M18 5v3");
}

.uokpg3btu {
  d: path("M12 5v3");
}

.yngda3bvc {
  d: path("M3 15h18");
}

</style>
