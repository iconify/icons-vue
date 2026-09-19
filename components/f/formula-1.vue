<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="we5iqbc6s"/><path class="aa_ebgivs"/><path class="vhxcorb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:formula-1" /></template>
<style>
.aa_ebgivs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.578 18.306h-20.79a7 7 0 0 0-4.95 2.05L3.5 29.694h5.922l6.568-6.567a3.5 3.5 0 0 1 2.475-1.025h16.317");
}

.vhxcorb8f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.422 29.694h5.922l3.357-3.356a1.5 1.5 0 0 1 1.061-.44h11.223");
}

.we5iqbc6s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.5 18.306h-5.922L27.189 29.694h5.922z");
}

</style>
