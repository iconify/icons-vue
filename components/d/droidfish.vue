<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="x4x3tk66q"/><path class="aipw1ck2k"/><path class="s2nz1lb0n"/><path class="sbx2u3baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:droidfish" /></template>
<style>
.aipw1ck2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 15.6v6.92m-2.88-3.46h5.76m-11.54 5.67c1.83 1.42 1.33 5.52.67 7");
}

.s2nz1lb0n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 11c4.1 1.28 10.59 4.68 10.59 9.53s-4.2 5.92-10.59 5.92s-10.59-1.09-10.59-5.94S19.9 12.26 24 11m0 23.52c3.3 0 8.29-.36 8.29-2S29.13 30 24 30s-8.29.85-8.29 2.49s4.99 2.03 8.29 2.03");
}

.sbx2u3baj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.66 24.73c-1.83 1.42-1.33 5.52-.67 7M24 34.52s5 2.85 8.66 2.85c5.91 0 7.66.06 9.18 2.67l-2.76 3.46a12.4 12.4 0 0 0-4.79-1.5c-2.12 0-7.44-.24-10.29-3.58C21.15 41.8 15.83 42 13.71 42a12.4 12.4 0 0 0-4.79 1.5L6.16 40c1.52-2.61 3.27-2.67 9.18-2.67C19 37.37 24 34.52 24 34.52");
}

.x4x3tk66q {
  cx: 24px;
  cy: 7.74px;
  r: 3.24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
