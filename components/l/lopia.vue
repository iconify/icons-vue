<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yn4hkivbi"/><path class="gsmw3gbii"/><ellipse class="nes_pbcbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lopia" /></template>
<style>
.gsmw3gbii {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m6.196 16.145l3.478 7.575L15.287 20m-2.903 16.586l4.53-9.641c10.055 3.239 3.812 10.094-2.075 4.417m13.21-6.309l3.79 8.685m4.869-7.34l-2.597-12.21l8.28 6.92m-6.496 1.469l4.17-3.412");
}

.nes_pbcbx {
  cx: 23.769px;
  cy: 17.462px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.8px;
  ry: 4.7px;
}

.yn4hkivbi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.578 37.626C9.05 35.533 4.763 30.105 4.535 24.064c-.27-4.465.953-9.212 5.737-11.602c6.463-3.228 14.05-2.992 21.079-2.24c2.66.38 5.34 1.06 7.939 1.756c4.843 1.298 5.128 6.137 2.772 9.663c-7.39 12.114-13.52 15.413-22.394 16.584c-1.651.098-3.518-.063-5.089-.6z");
}

</style>
