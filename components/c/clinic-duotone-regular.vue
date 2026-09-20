<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yge78fbvw"/><path class="fr20hdeft"/><path class="ptaeireto"/><path class="e8vupfb9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:clinic-duotone-regular" /></template>
<style>
.e8vupfb9c {
  d: path("M9.5 14h5");
}

.fr20hdeft {
  d: path("M3 20v-8h5V7h8v5h5v8Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ptaeireto {
  d: path("M12 11.5v5");
}

.yge78fbvw {
  fill: currentColor;
  d: path("M3 20v-8h5V7h8v5h5v8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
