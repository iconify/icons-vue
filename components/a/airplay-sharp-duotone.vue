<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="sei8sdsvm"/><path clip-rule="evenodd" class="mx9-lpb6q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:airplay-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mx9-lpb6q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.8 12.4L18.8 20.4C18.9298 20.5731 19 20.7836 19 21C19 21.5523 18.5523 22 18 22L6 22C5.4477 22 5 21.5523 5 21C5 20.7836 5.0702 20.5731 5.2 20.4L11.2 12.4C11.3889 12.1482 11.6852 12 12 12C12.3148 12 12.6111 12.1482 12.8 12.4Z");
  stroke: none;
}

.sei8sdsvm {
  stroke-opacity: 0.4;
  d: path("M5.1043 16L2 16L2 3L22 3L22 16L19.8957 16L18.8957 16");
}

</style>
