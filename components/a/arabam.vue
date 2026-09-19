<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d7p2yobkm"/><path class="fhmi20_pk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:arabam" /></template>
<style>
.d7p2yobkm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.969 32.358A8.358 8.358 0 1 1 31.09 18.31l.008 11.371a8.36 8.36 0 0 1-6.13 2.677z");
}

.fhmi20_pk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.088 6.925H42.5v34.149H31.088l.01-1.765a17.4 17.4 0 0 1-8.22 2.068C13.28 41.377 5.5 33.597 5.5 24S13.28 6.623 22.877 6.623c2.866 0 5.687.709 8.212 2.063z");
}

</style>
