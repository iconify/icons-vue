<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="raqt_k-oi"/><path class="yotog7btq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aetna" /></template>
<style>
.raqt_k-oi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3 24.248c14 14.588 28 13.863 42 0c-13.51-14.65-27.497-15.127-42 0");
}

.yotog7btq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.517 21.44a7 7 0 1 1-3.71-3.853L24.004 24z");
}

</style>
