<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r06wrm69z"/><path class="y9lzjg_4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hubitat" /></template>
<style>
.r06wrm69z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.35 11.3a21.5 21.5 0 1 1-25.854-7.048");
}

.y9lzjg_4l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13 18.874L24 9.85l10.875 9.023V32.56H15.938");
}

</style>
