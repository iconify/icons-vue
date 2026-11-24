<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k5cp64buq"/><path class="clv673b0n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dialpad-duocolor-sharp" /></template>
<style>
.clv673b0n {
  d: path("M6 4h.01M12 4h.01M18 4h.01M6 9h.01M12 9h.01M18 9h.01M6 14h.01M12 14h.01M18 14h.01");
}

.k5cp64buq {
  stroke-opacity: 0.4;
  d: path("M12 19h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
