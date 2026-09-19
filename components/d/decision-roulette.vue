<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xm9uzjeuh"/><path class="r8w4t5t8o"/><path class="ia6vz7blb"/><path class="jshk5-4pz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:decision-roulette" /></template>
<style>
.ia6vz7blb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.16 28.686a6.17 6.17 0 0 1-4.081 1.538c-3.425 0-6.202-2.787-6.202-6.224s2.777-6.224 6.202-6.224a6.2 6.2 0 0 1 5.904 4.32");
}

.jshk5-4pz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.377 21.802l3.757.305l.356-3.79m-.537 15.993l4.773 8.267M13.274 5.423l4.773 8.266m0 20.621l-4.773 8.267M34.747 5.386l-4.798 8.31M12.096 24H2.5m43 0h-9.596");
}

.r8w4t5t8o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.905 24c0 6.575-5.33 11.905-11.905 11.905S12.095 30.575 12.095 24S17.425 12.095 24 12.095S35.905 17.425 35.905 24");
}

.xm9uzjeuh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24S12.126 2.5 24 2.5S45.5 12.126 45.5 24");
}

</style>
