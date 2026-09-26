<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yw3lpkbij"/><path class="rckdhx75l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-cursor-duotone" /></template>
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

.yw3lpkbij {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 12C23 18.0751 18.0751 23 12 23C5.92487 23 1 18.0751 1 12C1 5.92487 5.92487 1 12 1C18.0751 1 23 5.92487 23 12Z");
  stroke: none;
}

</style>
