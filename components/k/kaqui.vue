<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k26gfw30d"/><path class="mhsqwnbuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kaqui" /></template>
<style>
.k26gfw30d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.4 4.5a4 4 0 0 0-4 4v31a4 4 0 0 0 4 4h23.2a4 4 0 0 0 4-4v-31a4 4 0 0 0-4-4z");
}

.mhsqwnbuq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.606 8.909L16.394 24l15.212 15.091");
}

</style>
