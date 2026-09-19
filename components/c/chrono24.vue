<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ufc956bzn"/><path class="y9z42g87d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:chrono24" /></template>
<style>
.ufc956bzn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.203 39.203c-8.398 8.398-22.008 8.398-30.406 0S.4 17.195 8.797 8.797s22.008-8.397 30.406 0");
}

.y9z42g87d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.405 11.405L24 24l8.814-8.814");
}

</style>
