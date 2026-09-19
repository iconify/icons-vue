<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mp9gy3bjf"/><circle class="vb1_i8bfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:allen" /></template>
<style>
.mp9gy3bjf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 5.5l-17.462 37h13.67l1.549-4.853h4.486l1.549 4.853h13.67z");
}

.vb1_i8bfp {
  cx: 24px;
  cy: 30px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
