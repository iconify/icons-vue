<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ek8rrebbc"/><circle class="gzvz-xb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:instrument-tuner" /></template>
<style>
.ek8rrebbc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.144 5.5L17.428 27.485c-1.665 1.956.296 3.626.296 3.626M40.067 8.84L21.351 30.824c-1.665 1.956-3.626.286-3.626.286m0 0l-8.083 9.495");
}

.gzvz-xb5d {
  cx: 8.88px;
  cy: 41.553px;
  r: 0.947px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
