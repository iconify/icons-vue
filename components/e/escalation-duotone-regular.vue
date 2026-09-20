<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="idkzwm6tv"/><path class="rjeyxjbim"/><path class="ext7qtobs"/><path class="ia95t8sod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:escalation-duotone-regular" /></template>
<style>
.ext7qtobs {
  d: path("M3 19h5v-5h5V9h6");
}

.ia95t8sod {
  d: path("m16 6 3 3 -3 3");
}

.idkzwm6tv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 19h5v-5h5V9h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rjeyxjbim {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 6 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
