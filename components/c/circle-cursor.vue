<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tx_ah59as"/><path class="rckdhx75l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-cursor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rckdhx75l {
  d: path("M10.3877 17.1457L7.52471 8.16244C7.39855 7.76656 7.77689 7.39543 8.1725 7.52702L17.1515 10.5135C17.5987 10.6623 17.6212 11.2838 17.1859 11.4643L13.4526 13.0116C13.3352 13.0602 13.2403 13.1508 13.1865 13.2654L11.3359 17.2071C11.1392 17.6262 10.5282 17.5866 10.3877 17.1457Z");
}

.tx_ah59as {
  d: path("M12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2Z");
}

</style>
