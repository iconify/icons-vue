<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nreq_9ofo"/><path class="csyuhrrop"/><path class="u0f6w1z_e"/><path class="n3p0zmbop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:budget-exceeded-outline-regular" /></template>
<style>
.csyuhrrop {
  d: path("M5 14V3h14v11");
}

.n3p0zmbop {
  d: path("M11 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nreq_9ofo {
  d: path("M2 11v10h20V11L12 21Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u0f6w1z_e {
  d: path("M12 6v3");
}

</style>
