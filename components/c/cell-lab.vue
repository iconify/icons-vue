<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pvkrtue5x"/><path class="ivk96kcdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cell-lab" /></template>
<style>
.ivk96kcdi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 18.5c3.04 0 5.5 2.46 5.5 5.5s-2.46 5.5-5.5 5.5s-5.5-2.46-5.5-5.5s2.46-5.5 5.5-5.5");
}

.pvkrtue5x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5c11.88 0 21.5 9.62 21.5 21.5S35.88 45.5 24 45.5S2.5 35.88 2.5 24S12.12 2.5 24 2.5");
}

</style>
