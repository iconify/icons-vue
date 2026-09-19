<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="qmdopnbar"/><path class="whx5a-b3w"/><path class="fnsgndo3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:adlmidi-player" /></template>
<style>
.fnsgndo3z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.5 10.5h33v27h-33zm2 0v-2m2.9 2v-2m2.9 2v-2m2.9 2v-2m2.9 2v-2m2.9 2v-2m2.9 2v-2m2.9 2v-2m2.9 2v-2m2.9 2v-2m2.9 2v-2m-29 31v-2m2.9 2v-2m2.9 2v-2m2.9 2v-2m2.9 2v-2m2.9 2v-2m2.9 2v-2m2.9 2v-2m2.9 2v-2m2.9 2v-2m2.9 2v-2m-33-25h2m-2 2.875h2m-2 2.875h2m-2 2.875h2M5.5 24h2m-2 2.875h2m-2 2.875h2m-2 2.875h2m-2 2.875h2m33-23h2m-2 2.875h2m-2 2.875h2m-2 2.875h2M40.5 24h2m-2 2.875h2m-2 2.875h2m-2 2.875h2m-2 2.875h2");
}

.qmdopnbar {
  cx: 30.882px;
  cy: 32.329px;
  r: 2.124px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.whx5a-b3w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.006 32.329v-9.442c3.014 0 4.494 1.522 4.494 4.721");
}

</style>
