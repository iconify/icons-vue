<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bmsuhzbfo"/><path class="d9jlt9bkf"/><path class="lh2ogl0sm"/><path class="zykhcj4gn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-loudly-crying-face" /></template>
<style>
.bmsuhzbfo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.957 39.308c.82-1.524.934-5.028.934-6.898c0-3.738-4.273-12.076-4.273-12.076m-5.608-.376s4.273 10.329 4.273 13.387c0 2.865-.935 7.478-.935 9.347M9.044 39.327c-.82-1.524-.935-5.047-.935-6.917c0-3.738 4.395-12.135 4.395-12.135m6.295.063s-5.082 9.949-5.082 13.007c0 2.865.935 7.477.935 9.347");
}

.d9jlt9bkf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.207 21.026c.386-.321 2.099-1.675 4.588-1.529c2.02.118 3.375 1.153 3.824 1.53m-25.239-.001c.387-.321 2.1-1.675 4.59-1.529c2.02.118 3.374 1.153 3.823 1.53");
}

.lh2ogl0sm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.5 23.998c-.002 11.873 9.623 21.5 21.497 21.501S45.498 35.878 45.5 24.005v-.007c0-11.872-9.626-21.497-21.5-21.497S2.5 12.126 2.5 23.998");
}

.zykhcj4gn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.551 33.906a4.448 4.448 0 0 0 8.898.004v-.004a4.448 4.448 0 0 0-8.897-.007z");
}

</style>
