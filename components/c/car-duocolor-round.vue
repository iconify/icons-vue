<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="guglhac8i"/><path class="o6creye4i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:car-duocolor-round" /></template>
<style>
.guglhac8i {
  stroke-opacity: 0.4;
  d: path("M8 14h.01M16 14h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o6creye4i {
  d: path("M12 18H6a2 2 0 0 1-2-2v-6l2-4c.613-1.226 1.774-2 3-2h6c1.226 0 2.387.774 3 2l2 4v6a2 2 0 0 1-2 2zm-6 0h2v2H6Zm10 0h2v2h-2ZM3 10h18");
}

</style>
