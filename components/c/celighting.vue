<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jk1cn1bwc"/><path class="zs3doys2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:celighting" /></template>
<style>
.jk1cn1bwc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.326 8.174a15.826 15.826 0 0 0 0 31.652h19.218A3.957 3.957 0 0 0 43.5 35.87a3.957 3.957 0 0 0-3.956-3.957H20.326a7.913 7.913 0 0 1-.106-15.826h19.324A3.957 3.957 0 0 0 43.5 12.13a3.957 3.957 0 0 0-3.956-3.956z");
}

.zs3doys2i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.326 20.044A3.957 3.957 0 0 0 16.37 24a3.957 3.957 0 0 0 3.957 3.957h19.217A3.957 3.957 0 0 0 43.5 24a3.957 3.957 0 0 0-3.956-3.956z");
}

</style>
