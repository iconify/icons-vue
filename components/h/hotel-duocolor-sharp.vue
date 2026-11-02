<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ru57a09hd"/><path class="hr453tq4n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hotel-duocolor-sharp" /></template>
<style>
.hr453tq4n {
  d: path("M3 21h18M5 21V3h14v18M8 7h.01M8 11h.01M12 7h.01M12 11h.01M16 7h.01M16 11h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ru57a09hd {
  stroke-opacity: 0.4;
  d: path("M9 16h6m-5 5v-5m4 5v-5");
}

</style>
