<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="af1-7bbmy"/><path class="mw8_iwbdm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:corner-radius-duocolor-sharp" /></template>
<style>
.af1-7bbmy {
  stroke-opacity: 0.4;
  d: path("M3 5V3h2");
}

.mw8_iwbdm {
  d: path("M3 21v-4m0 0C3 9.268 9.268 3 17 3h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
