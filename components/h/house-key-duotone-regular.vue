<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gd58hqb6m"/><path class="cib2dlbwm"/><path class="zrdou8b0n"/><path class="buon2iihn"/><path class="q8xy9tkjr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:house-key-duotone-regular" /></template>
<style>
.buon2iihn {
  d: path("M16 12v4");
}

.cib2dlbwm {
  d: path("M4 15v-5l4 -4 4 4v5Z");
}

.gd58hqb6m {
  fill: currentColor;
  d: path("M4 15v-5l4 -4 4 4v5Z");
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

.q8xy9tkjr {
  d: path("M20 12v4");
}

.zrdou8b0n {
  d: path("M12 12h9");
}

</style>
