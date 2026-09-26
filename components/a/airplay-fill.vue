<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uylrcubvl"/><path clip-rule="evenodd" class="jyim-db-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:airplay-fill" /></template>
<style>
.jyim-db-p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.6 13.4667L17.6 18.8C17.8596 19.1462 18 19.5673 18 20C18 21.1046 17.1046 22 16 22L8 22C6.8954 22 6 21.1046 6 20C6 19.5673 6.1404 19.1462 6.4 18.8L10.4 13.4667C10.7777 12.9631 11.3705 12.6667 12 12.6667C12.6295 12.6667 13.2223 12.9631 13.6 13.4667Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uylrcubvl {
  d: path("M4.1043 15.8632C2.8523 15.4715 2 14.3118 2 13L2 6C2 4.3431 3.3431 3 5 3L19 3C20.6569 3 22 4.3431 22 6L22 13C22 14.3118 21.1477 15.4715 19.8957 15.8632");
}

</style>
