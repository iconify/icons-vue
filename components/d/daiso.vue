<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jfzhts04a"/><path class="dp1vl9bff"/><path class="cohh1bbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:daiso" /></template>
<style>
.cohh1bbau {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.123 42.5L24 28.965L37.877 42.5");
}

.dp1vl9bff {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.123 31.108L24 17.573l13.877 13.535");
}

.jfzhts04a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.123 19.035L24 5.5l13.877 13.535");
}

</style>
