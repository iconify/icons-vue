<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ye6w9-vba"/><path class="de-ta9b9y"/><circle class="po6l10bki"/><circle class="y7beoxqee"/><circle class="ftn3ylbhe"/><circle class="cbz_mwleo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:einstein-island" /></template>
<style>
.cbz_mwleo {
  cx: 29.421px;
  cy: 38.36px;
  r: 0.75px;
  fill: currentColor;
}

.de-ta9b9y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 30.093l7.069 2.373c4.216 2.84 12.411 3.444 18.217.378L42.5 29.841l-6.84 4.828l.005 2.525c.005 2.524-2.298 4.38-4.573 4.38H13.467c-5.573 0-5.655-4.873-5.52-6.734zm17.529-1.273v6.036");
}

.ftn3ylbhe {
  cx: 24.731px;
  cy: 38.36px;
  r: 0.75px;
  fill: currentColor;
}

.po6l10bki {
  cx: 15.353px;
  cy: 38.36px;
  r: 0.75px;
  fill: currentColor;
}

.y7beoxqee {
  cx: 20.041px;
  cy: 38.36px;
  r: 0.75px;
  fill: currentColor;
}

.ye6w9-vba {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.207 10.437l19.984.297c3.67 5.14 5.317 11.287 2.374 19.715c-6.187-2.007-12.74-2.339-19.878.008c.312-7.116.211-14.071-2.48-20.019zm3.564-2.543c1.453-.249 2.823-1.334 4.483.018c1.66 1.351 2.804.72 4.517.091m.147 2.649V6.425");
}

</style>
