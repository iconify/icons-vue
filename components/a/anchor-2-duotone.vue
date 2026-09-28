<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cu0s7qbbw"/><path class="tv-ylcblu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:anchor-2-duotone" /></template>
<style>
.cu0s7qbbw {
  stroke-opacity: 0.4;
  d: path("M12 8L12 17.5M12 17.5C12 19.9853 9.9853 22 7.5 22C5.0147 22 3 19.9853 3 17.5L3 13.2071C3 12.931 3.2239 12.7071 3.5 12.7071C3.6326 12.7071 3.7598 12.7598 3.8536 12.8536L5 14M12 17.5C12 19.9853 14.0147 22 16.5 22C18.9853 22 21 19.9853 21 17.5L21 13.2071C21 12.931 20.7761 12.7071 20.5 12.7071C20.3674 12.7071 20.2402 12.7598 20.1464 12.8536L19 14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tv-ylcblu {
  fill: currentColor;
  d: path("M16 5C16 7.2091 14.2091 9 12 9C9.7909 9 8 7.2091 8 5C8 2.7909 9.7909 1 12 1C14.2091 1 16 2.7909 16 5Z");
  stroke: none;
}

</style>
