<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yt7xum_xl"/><rect class="qwzqzq-mg"/><path class="uu05xbb7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:harbor" /></template>
<style>
.qwzqzq-mg {
  width: 15.186px;
  height: 4.891px;
  x: 16.263px;
  y: 16.109px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.416px;
  ry: 1.416px;
}

.uu05xbb7v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.174 21l-1.948 15.054M28.665 21l1.317 18.599M17.846 11.19l5.872-3.498l5.872 3.54m-8.808-1.79v6.667m6.331-6.371v6.37");
}

.yt7xum_xl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 33.793l15.202-3.62l10.859 5.309L42.5 31.38M8.395 38.056L20.46 35.32l11.1 4.987l8.365-3.057");
}

</style>
