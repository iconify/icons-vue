<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="emyboub8n"/><path class="tbe304aqf"/><path class="d9vhqbbxx"/><path class="ng35sb6yg"/><path class="ys-dg812g"/><path class="fx7anki8e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:air-pressure-duotone-regular" /></template>
<style>
.d9vhqbbxx {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 16v-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.emyboub8n {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fx7anki8e {
  d: path("M12 16v-6");
}

.ng35sb6yg {
  d: path("M3 16a9 9 0 0 1 18 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tbe304aqf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ys-dg812g {
  d: path("M3 16h18");
}

</style>
