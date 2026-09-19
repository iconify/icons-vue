<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nn0q8el2y"/><path class="urhel6bhu"/><path class="wkx7epban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bitwarden-beta" /></template>
<style>
.nn0q8el2y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 38.183c6.81-3.618 11.25-8.486 11.25-12.506V9.523H24.018z");
}

.urhel6bhu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.13 43.332a2 2 0 0 0 1.74 0c8.794-4.282 15.354-10.894 15.354-17.655V6.527a1.997 1.997 0 0 0-1.997-1.996H9.773a1.997 1.997 0 0 0-1.997 1.997v19.15c0 6.76 6.56 13.372 15.354 17.653");
}

.wkx7epban {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.275 21.511a2 2 0 1 1 0 4h-3.3v-8h3.3a2 2 0 1 1 0 4m0 0h-3.3");
}

</style>
