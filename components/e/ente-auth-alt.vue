<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="h1swldzxg"/><path class="cfcy91bbp"/><path class="ba92vmb9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ente-auth-alt" /></template>
<style>
.ba92vmb9a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 43.5c6.914-1.65 16.116-9.964 16.116-20.127V11.561L24 4.5L7.884 11.56v11.813C7.884 33.536 17.086 41.85 24 43.5");
}

.cfcy91bbp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.056 22.12v-3.073a3.944 3.944 0 1 1 7.888 0v3.072");
}

.h1swldzxg {
  width: 13.432px;
  height: 10.294px;
  x: 17.284px;
  y: 22.119px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.177px;
  ry: 1.177px;
}

</style>
