<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v-33iky6p"/><path class="ap9gq30sy"/><path class="t43qc9b_n"/><path class="x3hw5zbys"/><path class="cw_gsq1ee"/><path class="f1eo93bii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gpu-cluster-outline-regular" /></template>
<style>
.ap9gq30sy {
  d: path("M15.5 4a2 2 0 0 1 2 -2H20a2 2 0 0 1 2 2v2.5a2 2 0 0 1 -2 2h-2.5a2 2 0 0 1 -2 -2Z");
}

.cw_gsq1ee {
  d: path("m11 11 2 2");
}

.f1eo93bii {
  d: path("m13 11 -2 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t43qc9b_n {
  d: path("M2 17.5a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2V20a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.v-33iky6p {
  d: path("M2 4a2 2 0 0 1 2 -2h2.5a2 2 0 0 1 2 2v2.5a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.x3hw5zbys {
  d: path("M15.5 17.5a2 2 0 0 1 2 -2H20a2 2 0 0 1 2 2V20a2 2 0 0 1 -2 2h-2.5a2 2 0 0 1 -2 -2Z");
}

</style>
