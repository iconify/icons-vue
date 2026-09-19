<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="gu5j8_bkv"/><path class="pqmu7hbbs"/></g><path class="pcpfodbfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bird" /></template>
<style>
.gu5j8_bkv {
  d: path("M33.716 21.768A10.52 10.52 0 0 0 24 15.258a10.52 10.52 0 0 0-9.716 6.51");
}

.pcpfodbfz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.799 29.619a4.213 4.213 0 1 1-4.07-5.304l13.771-.043m-15.023 3.064h10.015m-24.291 2.283a4.213 4.213 0 1 0 4.07-5.304L4.5 24.272m15.023 3.064H9.507");
}

.pqmu7hbbs {
  d: path("M31.038 21.711a8.126 8.126 0 0 0-14.076 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
