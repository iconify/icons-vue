<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ffvi-frdv"/><path class="isdphsbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bbl-be-express-pay" /></template>
<style>
.ffvi-frdv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.501 33.049h8.774L18.145 24l-4.87-9.049H4.5L9.37 24zm25.355 0h8.774L43.5 24l-4.87-9.049h-8.774L34.726 24z");
}

.isdphsbfk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.178 33.049h8.774L30.822 24l-4.869-9.049h-8.775L22.048 24z");
}

</style>
