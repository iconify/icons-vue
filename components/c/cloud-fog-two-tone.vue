<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="daqsd1btm"/><path class="zutn9rzfk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-fog-two-tone" /></template>
<style>
.daqsd1btm {
  stroke-opacity: 0.4;
  d: path("M4 16.4641C2.762 15.7496 2 14.4291 2 13C2 10.7909 3.791 9 6 9C6 5.6863 8.686 3 12 3C15.314 3 18 5.6863 18 9C20.209 9 22 10.7909 22 13C22 14.4291 21.238 15.7496 20 16.4641");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zutn9rzfk {
  d: path("M8 17H16M5 21H10M14 21H19");
}

</style>
