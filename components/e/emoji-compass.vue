<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v36ah1bct"/><path class="hnko-m70h"/><circle class="l6cd208_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-compass" /></template>
<style>
.hnko-m70h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.97 21.97L32.7 15.3l-6.67 10.73M24 13.125V9.5m0 29v-3.625M34.875 24H38.5m-29 0h3.625");
}

.l6cd208_p {
  cx: 24px;
  cy: 24px;
  r: 18.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.v36ah1bct {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.97 21.97L32.7 15.3l-6.67 10.73m-4.06-4.06L15.3 32.7l10.73-6.67");
}

</style>
