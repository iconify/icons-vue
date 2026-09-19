<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nihztstgy"/><circle class="n7n39_biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kai" /></template>
<style>
.n7n39_biw {
  cx: 29.318px;
  cy: 24px;
  r: 14.182px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nihztstgy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.012 37.142a14.2 14.2 0 0 1-5.33 1.04A14.18 14.18 0 0 1 4.5 24A14.18 14.18 0 0 1 18.682 9.818a14.2 14.2 0 0 1 5.358 1.05");
}

</style>
