<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="akrpkl41x"/><circle class="ec9hdybhs"/><path class="ga4l-nbgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:airqualitywa" /></template>
<style>
.akrpkl41x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 21.981V34.5a8 8 0 0 0 8 8h21a8 8 0 0 0 8-8V16.122");
}

.ec9hdybhs {
  cx: 24px;
  cy: 9.7px;
  r: 4.2px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ga4l-nbgs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 16.122h37m-37 13.825h37m-.93-13.825c-6.056 0-7.02 5.242-12.734 5.242s-5.557-1.584-11.662-1.584s-5.071 2.538-11.674 2.2m8.033 7.967c2.285 0 4.184 2.58 6.533 3.423c2.327.836 4.99-.538 7.415-.402c4.329.244 3.996 1.661 7.441 1.66c3.663-.002 4.933-1.463 7.578-1.98");
}

</style>
