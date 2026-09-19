<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rhfce0imt"/><path class="kmp_z2wsr"/><path class="hjmk8lbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:m64plus-fz-pro" /></template>
<style>
.hjmk8lbos {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.965 28.354l4.58-3.017l-3.672 8.53l4.644-3.12M23.183 42.501V26.027m8.352 16.433v-3.122h1.128c.638 0 1.155.469 1.155 1.048s-.517 1.048-1.155 1.048h-1.128m3.743 1.026v-3.122h1.128c.638 0 1.155.469 1.155 1.048s-.517 1.048-1.155 1.048h-1.128m1.128 0l1.128 1.025m2.63-3.121c.633 0 1.142.46 1.142 1.034v1.053c0 .573-.51 1.034-1.142 1.034s-1.14-.46-1.14-1.034v-1.053c0-.573.508-1.034 1.14-1.034");
}

.kmp_z2wsr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.672 15.765v16.472L23.183 42.5L6.694 32.238V15.764");
}

.rhfce0imt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.183 26.028L6.694 15.764L23.184 5.5l16.488 10.264z");
}

</style>
