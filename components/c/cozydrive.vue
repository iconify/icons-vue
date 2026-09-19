<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uf5nmcj5v"/><path class="utvxw3sie"/><path class="uhde9gb5x"/><path class="hrll78j7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cozydrive" /></template>
<style>
.hrll78j7d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 18.28h-39V37a2.18 2.18 0 0 0 2.17 2.2h34.65A2.18 2.18 0 0 0 43.5 37h0Z");
}

.uf5nmcj5v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.25 34.43h-8.8a3.71 3.71 0 1 1 0-7.42h0a3.4 3.4 0 0 1 .71.07v-.32a3.71 3.71 0 0 1 7.42 0v.32a4 4 0 0 1 .71-.07a3.71 3.71 0 1 1 0 7.42Z");
}

.uhde9gb5x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.68 13H24.77c-2-.1-5.93-4.23-8.19-4.23h-9.9A2.18 2.18 0 0 0 4.5 11h0v7.29h39v-3.42A1.83 1.83 0 0 0 41.68 13");
}

.utvxw3sie {
  fill: currentColor;
  d: path("M34.63 29.9a5.4 5.4 0 0 1-1.78.33a4.9 4.9 0 0 1-1.77-.33a.44.44 0 0 0-.59.23a.43.43 0 0 0 .22.58a5.8 5.8 0 0 0 2.13.41a5.8 5.8 0 0 0 2.16-.4a.45.45 0 0 0 .17-.61a.44.44 0 0 0-.53-.21Z");
}

</style>
