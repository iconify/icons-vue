<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fklnc8g5e"/><rect transform="rotate(45 22.74 22.74)" class="ggohcobfu"/><path class="wr-tncczp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:india-drug-index" /></template>
<style>
.fklnc8g5e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h16.714c8.989 0 16.286 7.297 16.286 16.286v4.428c0 8.989-7.297 16.286-16.286 16.286H9.5c-2.208 0-4-1.792-4-4v-29c0-2.208 1.792-4 4-4");
}

.ggohcobfu {
  width: 25.261px;
  height: 11.425px;
  x: 10.11px;
  y: 17.028px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.712px;
  ry: 5.712px;
}

.wr-tncczp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.215 15.75l4.63 4.628a1.327 1.327 0 0 1 0 1.876l-2.59 2.59a1.327 1.327 0 0 1-1.876 0l-4.629-4.63a3.16 3.16 0 0 1 0-4.464h0a3.16 3.16 0 0 1 4.465 0");
}

</style>
