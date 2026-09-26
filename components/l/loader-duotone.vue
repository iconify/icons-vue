<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nd1jfrq2a"/><path class="oa5ga5b4c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:loader-duotone" /></template>
<style>
.nd1jfrq2a {
  stroke-opacity: 0.4;
  d: path("M12 18L12 22M7.7574 16.2426L4.9289 19.0711M2 12L6 12M7.7574 7.7574L4.9289 4.9289");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oa5ga5b4c {
  d: path("M12 2L12 6M16.2426 7.7574L19.0711 4.9289M18 12L22 12M16.2426 16.2426L19.0711 19.0711");
}

</style>
