<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k29k6dcph"/><path class="fjvxtabao"/><path class="aqb1rt7vf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:little-file-explorer" /></template>
<style>
.aqb1rt7vf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.973 11.171v3.079H7.578v-3.079zm.001 0h17.447v3.079");
}

.fjvxtabao {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.974 8.093v3.079H7.579V8.093z");
}

.k29k6dcph {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 17.329v22.579h-39V17.329m35.921-3.079H43.5v3.079h-3.079zM4.5 11.171h3.079v6.158H4.5z");
}

</style>
