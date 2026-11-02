<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jvayet_ht"/><path class="ej-89sb5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-off-duocolor-sharp" /></template>
<style>
.ej-89sb5a {
  d: path("M20 20v1H4V5h1m6 0h9v9M4 9h5m6 0h5");
}

.jvayet_ht {
  stroke-opacity: 0.4;
  d: path("M16 3v2M2 2l20 20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
