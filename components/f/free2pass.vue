<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pcib6-bde"/><ellipse class="ifn54cbpy"/><path class="vqzdbtbeg"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:free2pass" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ifn54cbpy {
  cx: 35.955px;
  cy: 26.368px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.373px;
  ry: 6.312px;
}

.pcib6-bde {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.583 44.467V3.533");
}

.vqzdbtbeg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.033 19.022V30.96m9.275-12.735s-.187-3.563-4.57-3.557s-4.705 4.355-4.705 4.355m18.55-.61s.56 3.238-5.262 9.06l-4.201 4.201h9.462M6.671 25.71h9.719m14.193-7.297s-.186-3.752-4.57-3.745s-4.705 3.745-4.705 3.745");
}

</style>
