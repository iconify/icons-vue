<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="uul2cmi7x"/><path class="a79afyl1m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ledmote" /></template>
<style>
.a79afyl1m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16 7.64a2.37 2.37 0 1 0 .05 0Zm8 0A2.35 2.35 0 1 0 26.35 10A2.35 2.35 0 0 0 24 7.64m7.87 0A2.35 2.35 0 1 0 34.26 10a2.34 2.34 0 0 0-2.39-2.35ZM16 17h.05a2.33 2.33 0 1 1-.05 0m8 0za2.35 2.35 0 1 1-2.35 2.35A2.35 2.35 0 0 1 24 17m7.87 0a2.35 2.35 0 1 0 2.39 2.35A2.35 2.35 0 0 0 31.87 17M16 26.32h.05a2.33 2.33 0 1 1-.05 0m8 0za2.35 2.35 0 1 1-2.35 2.35A2.35 2.35 0 0 1 24 26.32m7.87 0a2.35 2.35 0 1 0 2.39 2.35a2.35 2.35 0 0 0-2.39-2.35M16 35.66h.05a2.33 2.33 0 1 1-.05 0m8 0zA2.35 2.35 0 1 1 21.65 38A2.35 2.35 0 0 1 24 35.66m7.87 0A2.35 2.35 0 1 0 34.26 38a2.35 2.35 0 0 0-2.39-2.35ZM13.74 14.58h20.87");
}

.uul2cmi7x {
  width: 26.59px;
  height: 39px;
  x: 10.7px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.77px;
}

</style>
