<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yxd4rnbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-newsweather" /></template>
<style>
.yxd4rnbcq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6 8a2 2 0 0 0-2 2v28a2 2 0 0 0 2 2h26.83v-9.17a2 2 0 0 1 2-2H44V10a2 2 0 0 0-2-2Zm38 20.83L32.83 40M9.08 33.42H26.5M9.08 14.58h29.84M9.08 24H26.5");
}

</style>
