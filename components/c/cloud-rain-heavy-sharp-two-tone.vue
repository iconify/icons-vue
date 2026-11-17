<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ke8lhybnl"/><path class="gje1hhuth"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-rain-heavy-sharp-two-tone" /></template>
<style>
.gje1hhuth {
  d: path("M6 16V22M10 16V22M14 16V22M18 16V22");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ke8lhybnl {
  stroke-opacity: 0.4;
  d: path("M2.825 15.5L2.536 15C2.185 14.392 2 13.702 2 13C2 10.791 3.791 9 6 9C6 5.686 8.686 3 12 3C15.314 3 18 5.686 18 9C20.209 9 22 10.791 22 13C22 13.702 21.815 14.392 21.464 15L21.175 15.5");
}

</style>
