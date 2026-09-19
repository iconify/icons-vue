<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u8yr__uiu"/><path class="o3ydt8bih"/><path class="epd7fjbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cozy" /></template>
<style>
.epd7fjbnz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.603 26.966c-.242.624-.598 1.205-1.267 1.672m9.992-1.672c.242.624.599 1.205 1.268 1.672");
}

.o3ydt8bih {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.17 27.802c2.285 2.493 7.343 2.528 9.638.066");
}

.u8yr__uiu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.833 18.136c-2.45-11.53-17.035-11.425-19.735-.113C4.169 20.063 2.944 31.915 9.88 36.76c1.713 1.197 3.805 1.727 5.895 1.727H32.89c.921 0 1.848-.083 2.73-.346c9.698-2.888 9.16-18.236-1.71-20.013z");
}

</style>
