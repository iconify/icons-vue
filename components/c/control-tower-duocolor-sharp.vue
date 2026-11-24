<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g2g42pj9c"/><path class="hwh_5dnuf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:control-tower-duocolor-sharp" /></template>
<style>
.g2g42pj9c {
  stroke-opacity: 0.4;
  d: path("m8 7l2 6m6-6l-2 6");
}

.hwh_5dnuf {
  d: path("M3 7h18l-4 6H7zm6 6v8m6-8v8M3 21h18M12 7V3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
