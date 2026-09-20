<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l61lugbmz"/><circle class="mwhu5f91p"/><path class="bjdtmibhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gomo-ph" /></template>
<style>
.bjdtmibhe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.272 19.752v5.777M9.5 5.5a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4z");
}

.l61lugbmz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.197 22.356a2.6 2.6 0 0 0-2.738-2.6C9.054 19.828 8 21.092 8 22.502v2.413a2.6 2.6 0 0 0 2.6 2.605a2.6 2.6 0 0 0 2.598-2.604H10.6m11.652 2.596v-7.76l3.885 7.768l3.884-7.757v7.757m-14.956-2.573a2.573 2.573 0 1 0 5.146 0v-2.622a2.573 2.573 0 1 0-5.146 0zm16.991 0a2.573 2.573 0 1 0 5.147 0v-2.622a2.573 2.573 0 1 0-5.147 0z");
}

.mwhu5f91p {
  cx: 39.272px;
  cy: 27.52px;
  r: 0.75px;
  fill: currentColor;
}

</style>
