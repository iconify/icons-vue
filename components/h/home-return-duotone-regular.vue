<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="spzyo2b3i"/><path class="e1qcs1bxx"/><path class="dl1_p5cre"/><path class="fhczogb-z"/><path class="f7p-qpb9c"/><path class="rfp-q_b_z"/><path class="lveb61hbp"/><path class="j_t6_obaj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:home-return-duotone-regular" /></template>
<style>
.dl1_p5cre {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 16h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e1qcs1bxx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 12v8h10v-8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.f7p-qpb9c {
  d: path("m3 12 7 -7 7 7");
}

.fhczogb-z {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18.5 13.5 16 16l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j_t6_obaj {
  d: path("M18.5 13.5 16 16l2.5 2.5");
}

.lveb61hbp {
  d: path("M16 16h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rfp-q_b_z {
  d: path("M5 12v8h10v-8");
}

.spzyo2b3i {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 12 7 -7 7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
