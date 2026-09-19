<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="efgsw1hed"/><circle class="lbgp9obns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:binaryeye-alt" /></template>
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

.efgsw1hed {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.71 32.012l.03-16.024m2.014 16.938l.025-17.852m2.016 18.413l.025-18.974m4.055 19.689l.025-20.403m2.016 19.891l.025-19.38m4.055 17.955l.025-16.53m-18.396 13.58l.042-10.63m24.442 10.63l.041-10.63m-2.077 11.951l.033-13.272");
}

.lbgp9obns {
  cx: 24px;
  cy: 24px;
  r: 15.761px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
