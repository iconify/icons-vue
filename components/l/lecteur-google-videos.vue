<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ll0g54h-q"/><path class="xl1v9sbss"/><path class="mo0veyujg"/><path class="fjtxw4b3c"/><circle class="p4a348b5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lecteur-google-videos" /></template>
<style>
.fjtxw4b3c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.7 27.6c.3 1.2-1.2 4.3-.7 6.7c.3 1.5 1.8 4.5 1.8 4.5m-18.7-8.2c-3.6 2.6 1.4 8.5 5.2 11.9");
}

.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

.mo0veyujg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.6 32.1c2.1-1.8 8.2-4.9 11.1-4.9s5.9 2.5 10.8 5.6");
}

.p4a348b5o {
  cx: 15.4px;
  cy: 15.8px;
  r: 3.4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xl1v9sbss {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 35.6c2.1-1.8 6.8-5.1 9.6-5.1S33.5 37.2 40 42.2");
}

</style>
