<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j2cif1-7c"/><path class="ldlms3b-m"/><path class="y13dkg2ua"/><circle class="et4btwg6u"/><path class="mlj-pib2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cricket" /></template>
<style>
.et4btwg6u {
  cx: 17.646px;
  cy: 32.18px;
  r: 3.505px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j2cif1-7c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.484 8.42a1.814 1.814 0 0 0-2.558 0L8.42 11.926a1.814 1.814 0 0 0 0 2.557l15.573 15.573l3.47.139l2.734-2.734l-.14-3.47z");
}

.ldlms3b-m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.462 30.196l2.734-2.734l7.226 7.226l-2.734 2.734z");
}

.mlj-pib2s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.315 16.518L25.14 27.343");
}

.y13dkg2ua {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.024 38.086l4.062-4.063l2.023 2.023l-4.063 4.062z");
}

</style>
