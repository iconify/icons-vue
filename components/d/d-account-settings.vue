<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="inronmbgb"/><path class="ayz34huwt"/><path class="nfhb2pb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:d-account-settings" /></template>
<style>
.ayz34huwt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.122 39.492c-9.226-.232-16.584-7.777-16.584-17.005c0-9.395 7.616-17.01 17.01-17.01c9.216 0 16.755 7.34 17.003 16.553");
}

.inronmbgb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.527 28.305l1.393 1.393l-2.896 2.896a5.24 5.24 0 0 0-6.03.98a5.242 5.242 0 1 0 8.428 1.43l8.396-8.394c.775-.775.863-1.934.197-2.6c-.66-.66-1.798-.58-2.572.167l-1.395-1.394z");
}

.nfhb2pb_d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.094 27.772c-1.366-2.04-3.35-3.567-5.66-4.27a6.77 6.77 0 0 0 3.883-6.117a6.77 6.77 0 1 0-13.54 0a6.77 6.77 0 0 0 3.882 6.115c-4.418 1.346-7.64 5.703-7.64 10.904V35.8m16.643 3.619a1.483 1.483 0 1 1-2.096-2.099a1.483 1.483 0 0 1 2.096 2.099m6.626-13.875l1.393 1.393");
}

</style>
