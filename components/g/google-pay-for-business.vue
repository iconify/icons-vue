<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hz35zdn2f"/><path class="uv_0d1oyb"/><circle class="drvzo818o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-pay-for-business" /></template>
<style>
.drvzo818o {
  cx: 31.978px;
  cy: 36.064px;
  r: 7px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hz35zdn2f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.32 16.44l2.5 1.44c1.73 1 2.31 3.2 1.32 4.92l-3.63 6.29M17.78 39.67a6.59 6.59 0 0 0 7.76-.87m-8.09.68a6 6 0 0 1-2.19-8.19l6.33-11a3.6 3.6 0 0 0-1.32-4.91l-4.6-2.65a3.58 3.58 0 0 0-4.897 1.287l-.013.023L5.63 23A8.38 8.38 0 0 0 8.7 34.42l3.56 2.06zM40.2 13.82a6.58 6.58 0 0 1 2.43 8.98c0 .01-.01.01-.01.02l-5.16 8.9");
}

.uv_0d1oyb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.17 14.2l1.48-2.56a8.4 8.4 0 0 1 11.47-3.07l3.56 2.06l5.19 3a6 6 0 0 0-8.19 2.2L23 30.8a3.6 3.6 0 0 1-4.91 1.32l-2.51-1.45m17.51 5.395l-3.297-.001m3.297.001c1.101 0 2 .9 2 1.999s-.899 2-2 2h-3.297v-8h3.3c1.1 0 2 .9 2 2s-.9 2-2 2z");
}

</style>
