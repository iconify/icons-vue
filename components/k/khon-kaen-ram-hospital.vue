<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sd-_hsb5o"/><path class="xm9uzjeuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:khon-kaen-ram-hospital" /></template>
<style>
.sd-_hsb5o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.738 35.402h8.36c1.265 0 1.322-.41.971-1.05L24 8.775L9.931 34.352c-.352.64-.294 1.05.971 1.05h8.36M24 23.595v8.455m4.227-4.227h-8.454");
}

.xm9uzjeuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24");
}

</style>
