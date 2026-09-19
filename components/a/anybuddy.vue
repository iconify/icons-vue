<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bkg5n6b5m"/><path class="nuh0pju5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:anybuddy" /></template>
<style>
.bkg5n6b5m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.55 14.638L24.256 5.5l17.194 9.138v18.337L24.255 42.5L6.55 32.974z");
}

.nuh0pju5w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.474 21.865c1.129 0 2.042.928 2.042 2.056s-.914 2.042-2.042 2.042h0a2.045 2.045 0 0 1-2.057-2.032v-.01c0-1.128.915-2.056 2.057-2.056m13.48 0c1.129 0 2.057.928 2.057 2.056s-.928 2.042-2.056 2.042s-2.042-.914-2.042-2.042h0a2.054 2.054 0 0 1 2.042-2.056m-4.512 8.554c.588 1.022.039 2.237-1.227 2.712s-2.768.032-3.357-.99a1.69 1.69 0 0 1 0-1.722z");
}

</style>
