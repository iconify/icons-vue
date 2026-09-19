<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t6r2_uw7l"/><path class="emgvzqbpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:1track" /></template>
<style>
.emgvzqbpy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.304 34.249L24 44.5L5.696 34.249V13.751L24 3.5l18.304 10.251z");
}

.t6r2_uw7l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.221 26.715l5.21-2.865v19.211");
}

</style>
