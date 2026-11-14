<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="akjtmscff"/><path class="v8nrpybvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:aquaponics" /></template>
<style>
.akjtmscff {
  d: path("M12.3 16.5H2.5v-13H19v8.1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v8nrpybvy {
  d: path("M5.75 9.5C7.75 7 11 7 12.5 9.5l2.5-2v4l-2.5-2C11 12 7.75 12 5.75 9.5Zm12.75 12v-4c0-2.25-1.5-3.25-3.75-3.25c0 2 1.5 3.25 3.75 3.25m0-.5c0-2 1.5-3.25 3.5-3.25c0 2-1.5 3.25-3.5 3.25");
}

</style>
