<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ydewsccpi"/><path class="suj4n5bih"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:language-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.suj4n5bih {
  stroke-opacity: 0.4;
  d: path("M16 11L18 11M12 15L22 15M14 15C14.4767 16.1439 15.5203 18.0076 17 19.543C18.1074 20.6922 19.459 21.6576 21 22M20 15C19.5234 16.1439 18.4797 18.0076 17 19.543C15.8926 20.6922 14.541 21.6576 13 22");
}

.ydewsccpi {
  d: path("M2 11L6 2L10 11M3.3333 8L8.6667 8");
}

</style>
