<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bur20ffrd"/><path class="j3mg9mb9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:keepsafe" /></template>
<style>
.bur20ffrd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.96 32.52V15.48h6.547V7.038H5.5v33.924h15.007V32.52z");
}

.j3mg9mb9b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.487 30.292L42.5 7.038H31.129L15.802 24l15.327 16.962H42.5L21.487 17.708");
}

</style>
