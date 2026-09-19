<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ofzyvez0d"/><path class="xo8g68b8w"/><path class="i2adz_b_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bunnings" /></template>
<style>
.i2adz_b_i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.3 29.2L17.5 42.5h11.7l7.2-5.1s4.5-3.3 4.5-9s-1.1-8.2-6.5-8.2v9z");
}

.ofzyvez0d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.1 22.5v8.9l23-17.8H18.6z");
}

.xo8g68b8w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.3 17.9V5.5H30c4.3 0 7.9 3.5 7.9 7.9s-3 6.9-5.4 8.2l-20.2 15v-9");
}

</style>
